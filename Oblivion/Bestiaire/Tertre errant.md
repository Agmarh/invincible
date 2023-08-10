```statblock
image: [[monstre.png]]
name: Tertre errant
size: G
type: Plante
subtype: 
alignment: Non aligné
ac: 15
hp: 136
hit_dice: 16d10+48
speed: 6 m, nage 6 m
stats: [18, 8, 16, 5, 10, 5]
skillsaves:
  - Discrétion: +2
damage_resistances: de feu et de froid
damage_immunities: de foudre
condition_immunities: [[Assourdi]], [[Aveuglé]], Epuisé
senses: vision aveugle 18 m (aveugle au-delà de cette distance), Perception passive 10
languages: -
cr: 5
traits:
  - name: Absorption de la foudre
    desc: "Chaque fois que le tertre errant devrait subir des dégâts de foudre, ceux-ci ne lui sont pas infligés et il récupère, à la place, un nombre de points de vie égal aux dégâts de foudre qu'il aurait dû subir."
actions:
  - name: Attaques multiples
    desc: "Le tertre errant effectue deux attaques de coup. S'il réussit ces deux attaques contre une cible de taille M ou plus petite, celle-ci est [[Empoigné]] (évasion DD 14) et le tertre errant utilise son _Enveloppement_ sur elle."
  - name: Coup
    desc: "Attaque d'arme au corps à corps : +7 pour toucher, allonge 1,50 m, une cible. Touché : 13 (2d8+4) dégâts contondants."
  - name: Enveloppement
    desc: "Le tertre errant enveloppe une créature de taille M ou plus petite qu'il empoigne. La cible enveloppée est [[Aveuglé]], [[Entravé]] et incapable de respirer. Elle doit réussir un jet de sauvegarde de Constitution DD 14 au début de chacun des tours du tertre errant pour ne pas subir 13 (2d8+4) dégâts contondants. Quand le tertre se déplace, la créature enveloppée se déplace avec lui. Le tertre ne peut pas envelopper plus d'une créature à la fois."
```
