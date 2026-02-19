# Changelog

All notable changes to POMPOMPURIN's KP will be documented in this file.

---

## [1.7.1] - 2/17/2026

- Added extra functions under Max Skips. It now has reposition on max skips and force attack on max skips. Reposition on max skips will do an Anti-Idle movement after reaching the threshold. Force attack on max skips will attack the current target regardless of the filter
- Added North and South direction for Idle Detection
- Modified code for validation of license, specifically for VMs users

---

## [1.7.0] - 2/16/2026

- Added Class on the top-right corner. It hides features applicable for other classes for better user-friendliness
- Added Timer (s) under Skills (Damage) tab. Good to use during boss hunts to maintain full uptime on damage over time (DoT) abilities
- Improved online database IP verification for users using 3+ VMs. The program should no longer invalidate user license key when using 3+ VMs
- Added Dadati Return key. The key is pressed when the program verifies the monster died, so Dadati returns around the character's vicinity. Available under Samabat Class drop-down

---

## [1.6.4] - 2/15/2026

- Introduced Dadati Attack under Opener Key for Samabats

---

## [1.6.3] - 2/12/2026

- Introduced Traditional mode under Skills (Buffs). It works similarly to traditional KP. It will ignore all CD verification and will press the button twice every x amount of seconds. Useful for braindead Vidya healing and skills with 0 CD
- Introduced Focus Rohati healing. It will ignore the rest of the party members for single-target heal (only uses Susaruba for other party members) and focus a specific party member for Rohati. Useful for 8-man parties with a Satya during boss hunt
- Hardcoded party_reference.png to remove file clutter

---

## [1.6.2] - 2/5/2026

- More fine tuning of Vidya buffing under Skills (Buffs)
- System log is now detachable from the KP for easier viewing
- Improved online database security logging

---

## [1.6.1] - 2/2/2026

- Introduced Anonymous Mode on Death Notifications
- The program will ALWAYS re-learn 1,9 0 and F1-F10 when previous instance of Kathana was closed and the user reconnects the program to the new instance of Kathana to remove stale memory
- Too many to count bug fixes on Save/Load state. It is the reason why despite users not messing with the settings, it doesn't function accordingly afterwards

---

## [1.6.0] - 1/30/2026

- Party Assist now ignores Target Filter monsters
- Party Assist interaction with Smart Loot revamped
- Vidya Party Heal now cancels ALL actions to prioritize healing party members. It requeues cancelled actions afterwards when party members are above the HP threshold
- KP is now usable with any features enabled. Having a Skills (Buffs) skill is no longer required
- Added Death Confirmation Movement. It uses Anti-Idle movement to move after monster death confirmation to still be able to target despite visual bug. Useful if everyone's on Party Assist in your party and you're the party leader
- Added Ded Bot, a Discord Webhook to notify you when your character is dead. You can edit the message posted, and it will be posted on the death-channel

---

## [1.5.6] 1/25/2026

- Target Filter is now always enabled, due to it being part of every feature. Turning it off breaks the KP
- Added Bar Color in Easy Setup Wizard for all HP/TP bar region captures
- Easy Setup Wizard is now resizable
- Fixed a coding error where the program crashes if you selected a region above or below its ideal threshold 
- Fixed a bug where Select Regions under Skills (Damage) tab still shows as "Not Set" after using Easy Setup Wizard

---

## [1.5.5] 1/24/2026

- ALL settings are now saved, including monsters in the Target Filter and Learn 1-9, 0, Learn F1-F10 states

---

## [1.5.4] 1/24/2026

- Removed Slot column and coded everything using Key for Skills (Damage) and Skills (Buffs)
- Added maximum two skills on Requires column (ex. Requires 2,3)
- Step-by-step Wizard to help with the complicated setup. It should simplify the setup for people that struggled with configuration, despite reading the guide

---

## [1.5.3] 1/23/2026

- Fixed interaction with Skills (Buffs) and Anti-Interrupt firing simultaneously, causing for the program to queue the buff twice

---

## [1.5.2] 1/22/2026

- Hotfix on Skills (Buffs) firing multiple times on low-CD abilities
Up and coming for v1.5.3
- Finetuning Skills (Buffs) with Anti-Interrupt to avoid timing conflicts with fast CD buffs
More UI/UX fixes
- An updated English/Spanish guide will also be provided soon.

---

## [1.5.1] 1/21/2026

- Dark Mode is now available under Settings tab

---

## [1.5] 1/18/2026

- New priority system for Vidya Party Heal. Will always use Susaruba if two or more are low HP on the party list
- Tightened the white pixel difference allowance from d=3 to d=2 for more a more accurate Target Filter
- Added an HP% threshold on Smart Targeting. It will skip monsters below that HP threshold, even if the Target Filter approves it. Could be disabled

---

<p align="center">
  <sub>For full details on each feature, see the <a href="docs/KP_GUIDE_UPDATED.pdf">documentation</a>.</sub>
</p>
