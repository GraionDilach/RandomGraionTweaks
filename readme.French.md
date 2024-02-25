# Random Graion Tweaks

Ce mod propose diverses modifications de Graion Dilach pour les jeux Infinity Engine.

## Composants 10 à 23 : Plus de parchemins de sorts aléatoires ( pour Enhanced Editions uniquement).

Inspiré par le composant "Plus vaste selection de parchemins aleatoires" de SCS, RandomGraionTweaks ajoute des parchemins de sorts aléatoires en possession des lanceurs de sorts profanes / divins.

Les parchemins ajoutés par des mods sont inclus uniquement qu'ils suivent la procédure standard de spell.ids où s'ils sont ajoutés grâce à l'outil d'OlvynChuru, **ClassSpellTool library**, version égale où supérieur à celle de 2023-02-08.

Les parchemins de sorts en double sont filtrés et retirés.

Les associations suivantes sont disponibles (chacune peut être choisie individuellement) :
* **10** : un parchemin de sort profane de même niveau que votre plus haut niveau de sort mémorisé.
* **11** : un parchemin de sort profane pouvant être de même niveau ou inferieur à votre plus haut niveau de sort mémorisé.
* **12** : un parchemin de sort profane de 4 niveaux de moins que le plus haut niveau de sort profane mémorisé.(donc si c'est un sort de niveau 5, le parchemin sera de niveau 1, le niveau 6 recevra un parchemin de niveau 2, etc.)
* **13** : un parchemin de sort profane égale ou inférieur à 4 niveaux de moins que le plus haut niveau de sort profane mémorisé.(donc si c'est un sort de niveau 5, le parchemin sera de niveau 1, à partir du niveau 6 le parchemin sera de niveau 2 ou inférieur, etc.)

---

* **20** : un parchemin de sort divin de même niveau que votre plus haut niveau de sort mémorisé.
* **21** : un parchemin de sort divin pouvant être de même niveau ou inferieur à votre plus haut niveau de sort mémorisé.
* **22** : un parchemin de sort divin de 4 niveaux de moins que le plus haut niveau de sort profane mémorisé.(donc si vous disposez de sorts de niveau 5, le parchemin sera de niveau 1, le niveau 6 recevra un parchemin de niveau 2, etc.)
* **23** : un parchemin de sort divin égale ou inférieur à 4 niveaux de moins que le plus haut niveau de sort profane mémorisé.(donc si vous disposez de sorts de niveau 5, le parchemin sera de niveau 1, à partir du niveau 6 le parchemin sera de niveau 2 ou inférieur, etc.)

Cela signifie qu'un Clerc / Mage de haut niveau peut obtenir jusqu'à 8 parchemins supplémentaires si tous les composants sont installés.

**COMPATIBILITÉ** : Ces composants doivent être installés après tous les mods qui pourraient améliorer l'IA des lanceurs de sorts (SCS). Ces composants on une fonction similaire à "Plus vaste sélection de parchemins aléatoires" de SCS, mais ils peuvent être installés ensemble. Ces composants **doivent** absolument être installés après le mod [Abel's Nonrandom Treasures](https://forums.beamdog.com/discussion/83483/mod-nonrandom-treasures) pour IWDEE.

## Components 3X Remplacer les flèches magiques clonées et marquées non-récupérables par des flèches similaires mais récupérables.

En fonction du sous-composant sélectionné, la quantité de flèches présentes sera revue à la baisse.
- __31:__ Conserver 100% des flèches concernées (Même quantité que les flèches non-récupérables présente sur la créature)
- __32:__ Conserver 75 % des flèches concernées
- __33:__ Conserver 66 % des flèches concernées
- __34:__ Conserver 50 % des flèches concernées
- __35:__ Conserver 33 % des flèches concernées
- __36:__ Conserver 25 % des flèches concernées

__COMPATIBILITY:__ Ce composant n'a pas été testé avec Item Revisions et ne prend pas en compte les changements apportés par ce mod. Ces composants ne modifieront pas les quantités de flèches individuelles et non-récupérables des créatures.

## Composant 4X Modifier la quantité d'or possédée par les créatures

Ce composant modifie la quantité d'or possédée par les créatures
- __41__ = Augmenter de 200%
- __42__ = Augmenter de 150%
- __43__ = Diminuer de 83%
- __44__ = Diminuer de 75%
- __45__ = Diminuer de 66%
- __46__ = Diminuer de 50%
- __47__ = Diminuer de 33%
- __48__ = Diminuer de 25%

**COMPATIBILITÉ** : Ces composants sont similaires à ceux disponible dans le mod Aurora's Shoes and Boots, à la différence que celui-ci n'utilise pas une liste de créatures spécifiques mais les affecte toutes, quelle que soit leur provenance.

## Composant 5X Modifier la valeur marchande des pièces de joaillerie et autres bijoux (n'affecte pas les amulettes / anneaux ayant des effets / capacités magiques).

- __51__ = Augmenter de 200%
- __52__ = Augmenter de 150%
- __53__ = Diminuer de 83%
- __54__ = Diminuer de 75%
- __55__ = Diminuer de 66%
- __56__ = Diminuer de 50%
- __57__ = Diminuer de 33%
- __58__ = Diminuer de 25%

**COMPATIBILITÉ** : Ces composants sont similaires à ceux disponible dans le mod Aurora's Shoes and Boots, à la différence que celui-ci n'utilise pas une liste d'Items spécifiques mais les affecte tous, quelle que soit leur provenance.

## Composant 6X Modifier le pourcentage de la somme demandée par les marchands pour ses articles.

Ce composant modifie le pourcentage de la somme demandée par les marchands pour ses articles.
- __61__ = Diminuer de 50%
- __62__ = Augmenter de 125%
- __63__ = Augmenter de 133%
- __64__ = Augmenter de 150%
- __65__ = Augmenter de 175%
- __66__ = Augmenter de 200%
- __67__ = Augmenter de 300%
- __68__ = Augmenter de 400%
- __69__ = Augmenter de 500%

**COMPATIBILITÉ** : Ces composants sont similaires à ceux disponible dans le mod Aurora's Shoes and Boots, à la différence que celui-ci n'utilise pas une liste de marchands spécifiques mais les affecte tous, quelle que soit leur provenance.

## Composant 7X Modifier le pourcentage de la somme payée par les marchands pour vos articles.

Ce composant modifie le pourcentage de la somme payée par les marchands pour vos articles.
- __71__ = Augmenter de 200%
- __72__ = Augmenter de 150%
- __73__ = Diminuer de 83%
- __74__ = Diminuer de 75%
- __75__ = Diminuer de 66%
- __76__ = Diminuer de 50%
- __77__ = Diminuer de 33%
- __78__ = Diminuer de 25%

**COMPATIBILITÉ** : Ces composants sont similaires à ceux disponible dans le mod Aurora's Shoes and Boots, à la différence que celui-ci n'utilise pas une liste de marchands spécifiques mais les affecte tous, quelle que soit leur provenance.

## Composant 100 Table mixte PnP-BG de sorts supplémentaires basés sur la sagesse.

Cela a été évoqué lors du développement du EE Fixpack, Bioware a fait une erreur en implémentant la façon dont les sorts supplémentaires sont configurés (ce qui n'a été corrigée que dans PST), en conséquence plus de sorts supplémentaires de niveau intermédiaire et moins de sorts supplémentaires de bas niveau. Ce composant tente de mélanger les deux options de sorte que les joueurs bénéficient des bonus pour les deux tables mais de manière cohérente, à l'exception d'une mise en garde : PnP et BG accordent le premier sort supplémentaire de niveau 4 pour une Sagesse de 18, ce qui rompt la logique, il est donc différé.

Le tableau complet :

| Sagesse \ Sorts supplémentaires   | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|-----------------------------------|---|---|---|---|---|---|---|
|                  13               | 1 | 0 | 0 | 0 | 0 | 0 | 0 |
|                  14               | 2 | 0 | 0 | 0 | 0 | 0 | 0 |
|                  15               | 2 | 1 | 0 | 0 | 0 | 0 | 0 |
|                  16               | 2 | 2 | 0 | 0 | 0 | 0 | 0 |
|                  17               | 2 | 2 | 1 | 0 | 0 | 0 | 0 |
|                  18               | 3 | 2 | 2 | 0 | 0 | 0 | 0 |
|                  19               | 3 | 3 | 2 | 1 | 0 | 0 | 0 |
|                  20               | 3 | 3 | 2 | 2 | 0 | 0 | 0 |
|                  21               | 4 | 3 | 3 | 2 | 1 | 0 | 0 |
|                  22               | 4 | 4 | 3 | 3 | 2 | 0 | 0 |
|                  23               | 4 | 4 | 4 | 3 | 2 | 1 | 0 |
|                  24               | 4 | 4 | 4 | 4 | 3 | 2 | 0 |
|                  25               | 4 | 4 | 4 | 4 | 4 | 3 | 1 |

**COMPATIBILITÉ** : Ce composant écrase le composant "Modifier la table des sorts divins en bonus lies à la sagesse" de Tweaks Anthology et écrase partiellement les sorts supplémentaires basés sur les statistiques de Scales of Balance.

## Composant 101 Accorder les emplacements de sorts du Rôdeur aux multiclasses Clerc / Rôdeur.

Par défaut, les jeux Infinity Engine n'accorde que le nombre d'emplacements de sorts disponibles pour les clercs aux personnages multiclassés Clerc / Rôdeur. Ce composant permet aux Clerc / Rôdeur de bénéficier également des emplacements de sorts accordés aux rôdeurs, en fonction du niveau du Rôdeur. (Ils pourront donc mémoriser plus de sorts...)

**COMPATIBILITÉ** : Ce composant ne devrait pas entrer en conflit avec d'autres mods. Vous devez l'installer après tous les mods et composants qui pourraient modifier le nombre d'emplacements disponibles pour les sorts de rôdeur.


## Composant 1000 Modifier les Worgs afin qu'ils utilisent les animations de IWD2.

En lieu et place de l'animation du loup simplement recoloré.

**COMPATIBILITÉ** : Ce composant devrait être installé après tous les mods qui ajoutent des monstres.

## Composant 1001 Modifier les Planétaires afin qu'ils utilisent les animations prévu pour SoD.

SoD inclut des animations pour les Planétaires inspirées des animations des Solaires, mais finalement ces animations sont restées inutilisées. Ce composant les associe donc aux planétaires.

**COMPATIBILITÉ** : Ce composant utilise une listes prédéfinie de créatures, merci de nous signaler si un planétaire a été oublié. Ce composant peut être utilisé avec les composants d'animation de P&P Celestials et Spell Revisions, si vous les installez en premier (Les Devas ne sont pas modifiés).

## Composant 1002 Remplacer l'animation du Dracolisk ajouté par le mode Made In Heaven par celle du Basilik de NWN Basilisk.

Le Dracolisk du mod Made in Heaven utilise une simple recoloration du Basilisk original. Ce composant le remplace par l'animation de NWN, le rendant ainsi réellement différent.

**COMPATIBILITÉ** :  Ce composant necessite un des composants inclus dans l'un des mods Made In Heaven et qui ajoute le Dracolisk.

## Composant 9999 Équiper les objets présents dans l'inventaire des créatures si des emplacements sont disponibles.

Ce composant passe en revue les inventaires des créatures et tente d'équiper tous les objets pour lesquels la créature a un emplacement de libre. Les objets déjà équipés ne sont pas altérés ou déplacés.

**COMPATIBILITÉ** : Ce composant est similaire à celui de Lolfixer, sauf qu'il ne tente pas de déplacer les objets déjà équipés. Pour un résultat optimal, il devrait être installé après tous les mods qui ajoutent des objets dans le jeu.

## Composant 10000 Sac à débordement.

Il est possible que l'installation d'un trop grand nombre de mods qui ajoutent du contenu ou des objets fasse disparaître de l'inventaire d'une créature certains objets essentiels. Ce composant passe en revue toutes les créatures et recueille tous les objets censés être **récupérables** mais n'ayant plus de place dans l'inventaire et les rassemble dans un sac à débordement dans le huitième emplacement de l'inventaire de la créature  (ce sac ne peut être subtilisé par la compétence Vol à la tire et ne peut être utilisé que pour récupérer les objets déjà présent à l’intérieur). Les objets non récupérables disparus à cause de l'installation de mégamods ne sont pas restaurés.

Voir [ici](https://www.gibberlings3.net/forums/topic/35016-do-cres-drop-all-their-assigned-items-or-is-there-a-limit-split-from-please-check-my-install-list-26-eet) pour le scénario que ce composant couvre.

Pour les autres moddeurs : toutes les données d'inventaire sont exportées au format texte dans "weidu_external\zgtweaks\equipdump\(spilled-)FILENAME" pour une éventuelle vérification. Les objets non récupérables disparus sont également listés et commentés.

**COMPATIBILITÉ** : Ce composant doit être installé en dernier dans votre installation. En raison du mode de fonctionnement de ce composant, il est possible qu'il présente un bug et/ou en provoque avec un autre mod. Veuillez signaler tout contenu suspect que vous constatez dans ces sacs.

## Remerciements

Thanks for argent77, subtledoctor, CamDawg and Luke for code snippets.
Thanks to yota13 for the Russian and JohnBob for the French translation.

## Mentions légales

This mod is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC. This mod is also not developed, supported, or endorsed by BioWare, Black Isle Studios, Interplay Entertainment Corp., Overhaul Games or Beamdog. All other trademarks and copyrights are property of their respective owners.
