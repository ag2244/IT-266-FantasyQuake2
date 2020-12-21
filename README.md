# IT-266-FantasyQuake2-game

## Setting up

  Included in this repository is a file called gamex86.dll. In order for the
mod to be run, a new folder must be created with the gamex86 file in it, as
well as a copy of all other files in the folder baseq2 in your Quake II Game
directory. This new folder should also be directly under this directory.

  In order to run the mod, you must create a new shortcut to the quake2
application. Right click on the new shortcut, click "Properties", and in the
"Target" bar under "Shortcut", add the line "+set game mod_test01" like so:

"C:\Program Files (x86)\GOG Galaxy\Games\Quake II\quake2.exe" +set game mod_test01

## Features
- Storm Spell: Shoots down multiple rockets from above an enemy in a damage shower
- Lightning Spell: Shoots lightning to instantly kill a singular enemy via hitscan
- Fire Spell: Fireball that explodes into multiple sparks for an area of damage
- Mana: New ammo type for spells

### Notes
Due to some issues with uploading the entire mod folder to github (Visual
Studio is now my mortal enemy) I was unable to upload the folder itself, just
the source code in the "game" project.
