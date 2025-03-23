# TALES OF DESTINY REFORGED v0.90
Released by mteam, Mar 24th 2025

Improves the presentation of the NTSC-U release of Tales of Destiny by correcting all known translation flubs and technical bugs, as well as reverting all instances of censorship and most other arbitrary localization changes.

In addition, modern Tales naming conventions have been implemented where applicable.

Although a sizable chunk of the script has been checked against the original Japanese, this patch is NOT a full-blown retranslation. The dialogue largely stays true to the original localization by Michiyo Pattillo, while ironing out obvious issues and reverting some decisions that were a product of the era.

One inspiration behind this was a defunct project in the same vein by Cless of Phantasian Productions fame.

![main menu before](https://mziab.grajpopolsku.pl/files/tod-reforged/main1.png) ![main menu after](https://mziab.grajpopolsku.pl/files/tod-reforged/main2.png)

![status screen before](https://mziab.grajpopolsku.pl/files/tod-reforged/status1.png) ![status screen after](https://mziab.grajpopolsku.pl/files/tod-reforged/status2.png)

![artes before](https://mziab.grajpopolsku.pl/files/tod-reforged/sartes1.png) ![artes after](https://mziab.grajpopolsku.pl/files/tod-reforged/sartes2.png)

![sprites before](https://mziab.grajpopolsku.pl/files/tod-reforged/bunny1.png) ![sprites after](https://mziab.grajpopolsku.pl/files/tod-reforged/bunny2.png)

![sprites before](https://mziab.grajpopolsku.pl/files/tod-reforged/cat1.png) ![sprites after](https://mziab.grajpopolsku.pl/files/tod-reforged/cat2.png)

For more screenshots click [here](https://mziab.grajpopolsku.pl/files/tod-reforged/)

DISCLAIMER
----------
No ownership is claimed by mziab or FlamePurge over Tales of Destiny or the franchise from which it originates. Commercial use of this patch, including but not limited to reproduction, sale, etc. is strictly prohibited.

This unofficial, fan-made patch is provided "as-is" on a voluntary (i.e. non-profit) basis. mziab and FlamePurge are not liable for damage incurred to the end-user, their OS, or their hardware while using this patch.

CREDITS
-------
- **mziab**: Hacking and tools, localization research, testing, font
- **FlamePurge**: Testing, suggestions, graphic edits
- **Phantasian Productions**: "New Arte!" pixel art and font from Tales of Phantasia PS1
- **DeJap**: Original font from Bahamut Lagoon (used in the Phantasian Productions patch)

CHANGES
-------
- A wide swath of translation and context errors have been corrected.

- New 8x8 font allowing for fully expanded item, special skill, spell, and enemy names.

- Meticulously readjusted menus to efficiently utilize space and improve their layouts.

- Fixed a bug where using Spectacles or the Inspect skill resulted in the incorrect enemy weakness displaying.
  
- Modern terms used for item, skill, spell, and enemy names where applicable. (Includes changing the "New Skill!" graphic to "New Arte!")

- Letters in the name entry screen are now properly aligned.

- Reverted censorship and localization changes in the graphics (sprites, overworld graphics, and items).

- Stahn starts equipped with a Technical Ring.

- Philia's name variable is used for her Philia Bomb skill, as well as other menu descriptions which reference her name.

- Leon's enemy name now consistently uses his name variable in all contexts.

- Corrected Lilith's default name.

- Lilith's name variable is used for her arte Lillith Slash.

- Lilith's proper avatar in the status screen is now shown at all times, not just at high Luck.
  (Please note that Lilith remains dummied out! The above changes were made for people who wish to cheat her into their party.)
  
- Cress/Arche use their modern Tales of Phantasia field map sprites.

- Restored the original opening FMV.

- Battle debug menu labels tweaked for clarity.

PATCHING INSTRUCTIONS
---------------------
This patch must be applied to the US release of Tales of Destiny (SLUS_006.26) in BIN+CUE format.

It is NOT meant for the PlayStation 2 game.

Some images of the game contain a dummy audio track; this isn't used, but it
complicates patching, as the dump might contain one or two .bin files.
To alleviate this, patches are provided for both:

- tod_reforged_v090.xdelta (use if your image has ONE .bin file)
  for a .bin file matching the following specifications:
    size: 600580848 bytes
    md5:  1762cd70d7a52f0358975fff362bb300

- tod_reforged_v090-track01.xdelta (use if your image has TWO .bin files)
  NOTE: apply this ONLY to track01
  for a .bin file matching the following specifications:
    size: 557790912 bytes
    md5:  21ca0eb29b32856d334a7cedbf5cc314

The patch can be applied using DeltaPatcher or the RHDN web-based patcher
available at https://www.romhacking.net/patch/
