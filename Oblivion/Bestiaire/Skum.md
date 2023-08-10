```statblock
image: [[monstre.png]]
name: Skum
size: M
type: Aberration
subtype: 
alignment: Loyal Mauvais
ac: 12
hp: 71
hit_dice: 13d8+13
speed: 9 m, nage 9 m
stats: [17, 11, 13, 10, 10, 4]
skillsaves:
  - Discrétion: +2
  - Perception: +2
senses: vision dans le noir 18 m, Perception passive 12
languages: commun des profondeurs
cr: 2
traits:
  - name: Amphibie
    desc: "L’amphibe peut respirer l’air et l’eau.

_**Attaques multiples**_. Un amphibe sans arme effectue 3 attaques : 1 en mordant et 2 avec sa lance.

_**Morsure**_. attaque d’arme au corps à corps : +6 pour toucher, allonge 1,50 m, une cible. Touché : 7 (1d8+3) dégâts perforants.

_**Lance**_. attaque d’arme de jet ou au corps à corps. +6 pour toucher, allonge 1,50 m ou portée 6 m/18 m, une cible. Touché : 6 (1d6+3) dégâts perforants ou 7 (1d8+3) dégâts perforants si elle est utilisée à deux mains au corps à corps.

_**Filet**_. attaque d’arme de jet. +6 pour toucher, portée 1,5 m/4,5 m, une cible d’une catégorie de taille Grande ou inférieure. Touché : la cible est entravée. Elle peut effectuée son action pour faire un test de Force (DD 10) pour tenter de se libérer ou pour libérer une autre créature à portée. Une réussite du test met fin à l’effet du filet. En infligeant 5 points de dégâts tranchants au filet (CA 10), il est possible de libérer les victimes sans les blesser, mais cela détruit le filet."
  - name: Avantage aquatique
    desc: "Sous l’eau, l’amphibe bénéficie d’un avantage à ses tests de Discrétion et de Perception, ainsi qu’à ses jets de sauvegarde de Dextérité visant à éviter un danger. S’il nage en ligne droite, il peut utiliser l’action de course."
  - name: Pattes arrières
    desc: "L’amphibe gagne 2 attaques de griffes supplémentaires avec ses pattes arrières lorsqu’il attaque en nageant."
actions:
  - name: Attaques multiples
    desc: <trait-description>
  - name: Morsure
    desc: <trait-description>
  - name: <trait-name>
    desc: <trait-description>
  - name: <trait-name>
    desc: <trait-description>
```
