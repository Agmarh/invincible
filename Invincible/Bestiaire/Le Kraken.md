```statblock
image: [[monstre.png]]
name: Le Kraken
size: GIG
type: Créature monstrueuse
subtype: 
alignment: Neutre
ac: 18 (armure naturelle)
hp: 232
hit_dice: 15d20+75
speed: 6m, nage 18m
stats: [24, 11, 20, 12, 10, 12]
saves:
  - For: +12
  - Dex: +5
  - Con: +10
  - Sag: +6
condition_immunities: [[Terrorisé]], [[Paralysé]]
senses: Vision dans le noir 36m, Perception passive 11
languages: aucune
cr: 15
traits:
  - name: Amphibie
    desc: "Le kraken peut respirer l'air et l'eau."
  - name: Monstre assiégeur
    desc: "Le kraken inflige des dégâts doublés aux objets et aux structures."
actions:
  - name: Attaques multiples
    desc: "Le kraken effectue trois attaques de tentacule et peut remplacer l'une d'elles par une utilisation de Projection ou une morsure."
  - name: Morsure
    desc: "Attaque d'arme au corps à corps : 12 (1d20+12) pour toucher, allonge 1,50 m, une cible. Touché : 17 (3d6+7) dégâts perforants."
  - name: Tentacule
    desc: "Attaque d'arme au corps à corps : +12 pour toucher, allonge 9 m, une cible. Touché : 14 (2d6+7)dégâts contondants et la cible est empoignée (évasion
DD 18). La cible est entravée jusqu'au terme de
cette empoignade. Le kraken possède dix tentacules
qui peuvent chacun empoigner une cible."
  - name: Projection
    desc: <trait-description>
```
