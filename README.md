What Is It
---

BetterKeybinds is a Witcher 3 mod that adds additional keybinds for PC players to be able to use all of their awesome buttons as well as makes a slight tweak to the HardLock mechanic so that it doesn't track the camera (subject to change).

New Keybinds:
---

New Keybinds | Planned | Implemented 
---|---|---
Instant Cast Signs | ✓ | ✓
Toggle Next Quickslot | ✓ | ✓
Draw Auto Sword | ✓ | ✓ (WIP)
Instant Use Quickslot | ✓ | 
Sheathe Either Sword | ✓ | ✓
Cancel Aiming | ✓ | ✓
Target Closest | ✓ | ✓
Target Cycle | ✓ | ✓ (WIP)
Discard Target | ✓ | 
Alternate Keybinds | ? |  

Install Instructions
----

Step 1: Install script mod

	- Copy modBetterKeybinds into your %GAMEDIR%\mods directory

Step 2: Install new rebind menu

	- input.xml location: %GAMEDIR%\bin\config\r4game\user_config_matrix\pc\input.xml
	- Backup old input.xml (I normally zip into input.xml.old.zip)
	- Copy new one and overwrite
	- If have a mod that already changes this file, you can easily merge the two, my changes are clearly marked, though I would use mine as a base

Step 3: Add in new keybinds (not bound to anything)

	- input.settings default location: %My Documents%\The Witcher 3\input.settings
	- Backup old input.settings
	- Open input.settings.BetterKeybinds.txt
	- Copy entire contents of input.settings.BetterKeybinds.txt
	- Paste into input.settings at the TOP


Mod Conflicts
---

Right now, I modify two script files:

`\scripts\game\player\playerInput.ws`
`\scripts\game\player\r4Player.ws`

The changes that I make are *easily* mergeable, use Script Merger to merge if you have other mods that modify these files.


Contributing
---

My edits are licenced under the MIT license, my code is your code. If you want to contribute code directly, submit a pull request on GitHub and I'll take a look.

Submit bugs and feature requests through the GitHub issue tracker please!
