What Is It
---

BetterKeybinds is a Witcher 3 mod that adds additional keybinds for PC players to be able to use all of their awesome buttons as well as introduces a target system that uses a hybrind HardLock (without CameraLock) so that you can keep a target without the camera tracking it.


Version
---

This is for ***only*** Witcher 3 1.12 and as of right now, only has an english localization.


New Keybinds:
---

New Keybinds | Implemented 
---|---
Instant Cast Signs | ✓ (No hold for alternate yet)
Instant Throw Bombs | ✓ (No hold for aim yet)
Toggle Next Quickslot | ✓
Switch to Specific Quickslot | ✓
Draw Auto Sword | ✓
Sheathe Either Sword | ✓
Cancel Aiming | ✓ 

BetterKeybinds also comes with a new targeting system for Witcher 3 that takes a hybrid approach where the camera is not locked onto the target. This allows for camera use similar to SoftLock mode (default mode without a target) but with a target selected, very useful for taking down particular targets one at a time in a fight!

New Keybinds | Implemented 
---|---
Target Closest | ✓ 
Target Cycle | ✓ (WIP)
Discard Target | ✓


Install Instructions
----

Step 1: Install script mod

	- Copy modBetterKeybinds into your %GAMEDIR%\mods directory

Step 2: Install new rebind menu

	- input.xml location: %GAMEDIR%\bin\config\r4game\user_config_matrix\pc\input.xml
	- Backup old input.xml (I normally zip it up)
	- Copy new one and overwrite
	- If have another mod that already changes this file, you can easily merge the two, my changes are clearly marked, though I would use mine as a base

Step 3: Install new default keybinds

	- input_qwerty.ini location: %GAMEDIR%\bin\config\r4game\legacy\base\input_qwerty.ini
	- Backup old input_qwerty.ini (I normally zip it up)
	- Copy new one and overwrite

Step 4: Reset your keybinds ingame



Mod Conflicts
---

Right now, I modify two script files:

`\scripts\game\player\playerInput.ws`
`\scripts\game\player\r4Player.ws`

The changes that I make are *easily* mergeable, use [Script Merger](http://www.nexusmods.com/witcher3/mods/484/?) to merge if you have other mods that modify these files.


Contributing
---

My edits are licenced under the MIT license, my code is your code. If you want to contribute code directly, submit a pull request on GitHub and I'll take a look.

Submit bugs and feature requests through the GitHub issue tracker please!
