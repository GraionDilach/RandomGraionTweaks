# Random Graion Tweaks

This mod features various tweaks by Graion Dilach for games on the Infinity Engine.

## Components 10-23 More Random Spell Scrolls (EE games only)

Inspired by SCS's "Wider spell scrolls" component, these components add random arcane spell scrolls the arcane/divine spellcasters. The random spell scrolls include mod-added scrolls only _if they follow the spell.ids standard_ currently (scrolls of spells added through the OlvynChuru ClassSpellTool are not included). Duplicate spell scrolls are filtered out.

The following combinations are offered (each can be selected individiually):
 - __10:__ one arcane scroll on the level of the highest arcane level memorized
 - __11:__ one arcane scroll up to the level of the highest arcane level memorized
 - __12:__ one arcane scroll on the level above 4 of the highest arcane level memorized (so if it's a level 5 spell, the scroll will be level 1, level 6 will receive level 2 scroll etc.)
 - __13:__ one arcane scroll up to the level above 4 of the highest arcane level memorized (so if it's a level 5 spell, the scroll will be level 1, level 6 will receive up to level 2 scroll etc.)
 - __20:__ one arcane scroll on the level of the highest divine level memorized
 - __21:__ one arcane scroll up to the level of the highest divine level memorized
 - __22:__ one arcane scroll on the level above 4 of the highest divine level memorized (so if it's a level 5 spell, the scroll will be level 1, level 6 will receive level 2 scroll etc.)
 - __23:__ one arcane scroll up to the level above 4 of the highest divine level memorized (so if it's a level 5 spell, the scroll will be level 1, level 6 will receive up to level 2 scroll etc.)

This means that a high-level Cleric-Mage can end up with up to 8 additional scrolls if all components are installed.

__COMPATIBILITY:__ These components should be installed after all mods which might buff spellcaster AI (SCS). These components functionally overlap with SCS's "Wider spell scrolls" but they can be installed together. These components __need__ to be installed after [Abel's Nonrandom Treasures](https://forums.beamdog.com/discussion/83483/mod-nonrandom-treasures) mod on IWDEE.

## Component 100 Mixed PnP-BG wisdom-based bonus spells table

As discussed during the development of the EE Fixpack, Bioware made an error when they implemented a feature with the way the bonus spells are set up (which was only fixed in PST), resulting with more bonus mid-level spells and less low-level bonus spells than intended. This component tries to blend both options so that players will end up having the bonuses of both tables consistently excluding one caveat: both PnP and BG provides the first level 4 bonus spells on Wisdom 18 which breaks a pattern and is thereby delayed.

The full table:

| Wisdom\Bonus spells | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---------------------|---|---|---|---|---|---|---|
|                  13 | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
|                  14 | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
|                  15 | 2 | 1 | 0 | 0 | 0 | 0 | 0 |
|                  16 | 2 | 2 | 0 | 0 | 0 | 0 | 0 |
|                  17 | 2 | 2 | 1 | 0 | 0 | 0 | 0 |
|                  18 | 3 | 2 | 2 | 0 | 0 | 0 | 0 |
|                  19 | 3 | 3 | 2 | 1 | 0 | 0 | 0 |
|                  20 | 3 | 3 | 2 | 2 | 0 | 0 | 0 |
|                  21 | 4 | 3 | 3 | 2 | 1 | 0 | 0 |
|                  22 | 4 | 4 | 3 | 3 | 2 | 0 | 0 |
|                  23 | 4 | 4 | 4 | 3 | 2 | 1 | 0 |
|                  24 | 4 | 4 | 4 | 4 | 3 | 2 | 0 |
|                  25 | 4 | 4 | 4 | 4 | 4 | 3 | 1 |

__COMPATIBILITY:__ This component overwrites Tweaks Anthology's Alter Wisdom-Based Divine Bonus Spell Table component and partially overwrites Scales of Balance's Stat-based Bonus Spells.

## Component 1000 Change Worgs to use IWD2 artwork

Instead of the regular recolored wolf animation.

__COMPATIBILITY:__ This component should be installed after all mods which might add monsters.

## Component 10000 Bag of Spilling

There is a possibility that installing too many content/item mods pushes out some of the crucial items from a creature's inventory. This component goes through all creatures and collect all such supposed to be __droppable__ but no longer available items and collects them into an unstealable one-way Bag of Spilling to the creature's eighth inventory slot. Undroppable items lost due to megamod installations are not recovered.

See [here](https://www.gibberlings3.net/forums/topic/35016-do-cres-drop-all-their-assigned-items-or-is-there-a-limit-split-from-please-check-my-install-list-26-eet) for the scenario this component covers.

For other modders: all the inventory data are exported to plaintext to weidu_external\zgtweaks\equipdump\(spilled-)FILENAME format for possible review. Undroppable spilled items are also listed and commented out.

__COMPATIBILITY:__ This component needs to come last in your install order. Due to the principle this mod component works, it is possible it exposes a bug in itself and/or in a different mod. Please report any suspicious content you see in these bags.

## Acknowledgements

Thanks for argent77, subtledoctor, CamDawg and Luke for code snippets.

## Disclaimer

This mod is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC. This mod is also not developed, supported, or endorsed by BioWare, Black Isle Studios, Interplay Entertainment Corp., Overhaul Games or Beamdog. All other trademarks and copyrights are property of their respective owners.
