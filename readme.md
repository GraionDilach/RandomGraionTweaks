# Random Graion Tweaks

### [Readme in French](https://github.com/GraionDilach/RandomGraionTweaks/blob/master/readme.French.md) | [Forum thread on G3](https://www.gibberlings3.net/forums/topic/34458-random-graion-tweaks/)

This mod features various tweaks by Graion Dilach for games on the Infinity Engine.

## Components 10-23 More Random Spell Scrolls (EE games only)

Inspired by SCS's "Wider spell scrolls" component, these components add random arcane spell scrolls the arcane/divine spellcasters. The random spell scrolls include mod-added scrolls only _if they either follow the spell.ids standard or was added with OlvynChuru's ClassSpellTool library, dated 2023-02-08 or later_ . Duplicate spell scrolls are filtered out.

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

## Components 3X Replace nondroppable magic arrow clones with their droppable counterparts

Depending on the subcomponent chosen, the quantity of the arrows in the stack will be decreased.
- __31:__ Keep 100% of the stack (no change on amount)
- __32:__ Keep 75% of the stack
- __33:__ Keep 66% of the stack
- __34:__ Keep 50% of the stack
- __35:__ Keep 33% of the stack
- __36:__ Keep 25% of the stack

__COMPATIBILITY:__ This component wasn't tested against Item Revisions and doesn't consider changes from that mod. These components won't change individual arrow stacks which are marked as non-droppable on creatures.

## Components 4X Change the amount of gold carried by monsters

These components change the amount of gold carried by the monsters.
- __41__ Increase to 200%
- __42__ Increase to 150%
- __43__ Decrease to 83%
- __44__ Decrease to 75%
- __45__ Decrease to 66%
- __46__ Decrease to 50%
- __47__ Decrease to 33%
- __48__ Decrease to 25%

__COMPATIBILITY:__ These components are similar to a group of components in Aurora's Shoes and Boots except that this one doesn't use an internal list and will affect all creatures, regardless of source of origin.

## Components 5X Change the value of standard jewellery (does not affect amulets/rings with magical effects/abilities)

- __51__ = Increase to 200%
- __52__ = Increase to 150%
- __53__ = Decrease to 83%
- __54__ = Decrease to 75%
- __55__ = Decrease to 66%
- __56__ = Decrease to 50%
- __57__ = Decrease to 33%
- __58__ = Decrease to 25%

__COMPATIBILITY:__ These components are similar to a group of components in Aurora's Shoes and Boots except that this one doesn't use an internal list and will affect all jewellery/gems without magical abilities, regardless of source of origin.

## Components 6X Change the percentage of the money merchants demand for an item

These components change the value of items, basically.
- __61__ = Decrease to 50%
- __62__ = Increase to 125%
- __63__ = Increase to 133%
- __64__ = Increase to 150%
- __65__ = Increase to 175%
- __66__ = Increase to 200%
- __67__ = Increase to 300%
- __68__ = Increase to 400%
- __69__ = Increase to 500%

__COMPATIBILITY:__ These components are similar to a group of components in Aurora's Shoes and Boots except that this one doesn't use an internal list and will affect all stores, regardless of source of origin.

## Components 7X Change the percentage of the money merchants pay for an item

These components change the selling value of items, basically.
- __71__ = Increase to 200%
- __72__ = Increase to 150%
- __73__ = Decrease to 83%
- __74__ = Decrease to 75%
- __75__ = Decrease to 66%
- __76__ = Decrease to 50%
- __77__ = Decrease to 33%
- __78__ = Decrease to 25%

__COMPATIBILITY:__ These components are similar to a group of components in Aurora's Shoes and Boots except that this one doesn't use an internal list and will affect all stores, regardless of source of origin.

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

## Component 101 Grant Ranger spell slots to Cleric-Ranger multiclasses

By default, the Infinity Engine only grants Cleric spell slots to C/R multiclasses. This component allows C/Rs to receive the Ranger spell slots as well, tied to the character's ranger level.

__COMPATIBILITY:__ This component shouldn't conflict with other mods. You need to install it after all mod components which would change the amount of ranger spell slots though.

## Component 1000 Change Worgs to use IWD2 artwork

Instead of the regular recolored wolf animation.

__COMPATIBILITY:__ This component should be installed after all mods which might add monsters.

## Component 1001 Change Planetars to use their SoD solar-based artwork

SoD included Planetar animations derived from the Solar animations, but these animations ended up unused. This component assggns them to the actual planetars.

__COMPATIBILITY:__ This component uses static monster lists, so please report if a planetar was missed. This component can be combined with the animation components of P&P Celestials and Spell Revisions, if you install those first (it will not touch the devas).

## Component 1002 Use NWN Basilisk artwork from Infinity Animations for Made in Heaven Dracolisk

The Made in Heaven Dracolisk uses a Basilisk recolor by default. This component changes it to be an NWN Basillisk, making it visually different.

__COMPATIBILITY:__ This component requires a Made in Heaven component which installed the Dracolisk.

## Component 9999 Equip items from inventory to fill empty slots

This component goes through creature inventories and attempt to equip all the items which the creature has a spare inventory slot for. Already-equipped items are not changed or touched.

__COMPATIBILITY:__ This component is similar to a component in Lolfixer, except that this one does not attempt to move already-equipped items. For best results, it should be installed after all mods which add items to the game.

## Component 10000 Bag of Spilling

There is a possibility that installing too many content/item mods pushes out some of the crucial items from a creature's inventory. This component goes through all creatures and collect all such supposed to be __droppable__ but no longer available items and collects them into an unstealable one-way Bag of Spilling to the creature's eighth inventory slot. Undroppable items lost due to megamod installations are not recovered.

See [here](https://www.gibberlings3.net/forums/topic/35016-do-cres-drop-all-their-assigned-items-or-is-there-a-limit-split-from-please-check-my-install-list-26-eet) for the scenario this component covers.

For other modders: all the inventory data are exported to plaintext to weidu_external\zgtweaks\equipdump\(spilled-)FILENAME format for possible review. Undroppable spilled items are also listed and commented out.

__COMPATIBILITY:__ This component needs to come last in your install order. Due to the principle this mod component works, it is possible it exposes a bug in itself and/or in a different mod. Please report any suspicious content you see in these bags. This component can be combined wiith the "Equip items from inventory to fill empty slots" component above, but that one must come before this one.

## Acknowledgements

Thanks for argent77, subtledoctor, CamDawg and Luke for code snippets.
Thanks to yota13 for the Russian and JohnBob for the French translation.

## Disclaimer

This mod is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC. This mod is also not developed, supported, or endorsed by BioWare, Black Isle Studios, Interplay Entertainment Corp., Overhaul Games or Beamdog. All other trademarks and copyrights are property of their respective owners.
