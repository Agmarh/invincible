Le ruinard est un charognard étrange que l’on trouve parfois dans les réseaux souterrains, souvent dans les égouts. Nul ne sait d’où vient ce mélange géant entre un ver et un mille-pattes, à la bouche garnie de crocs puissants et entourée de mandibules tranchantes, mais il se repaît la plupart du temps des animaux et déchets qui traînent dans les couloirs qu’il parcourt. Et parfois des malheureux qui se retrouvent face à lui. Solitaire, il arrive que l’on le trouve avec deux ou trois de ses congénères, surtout en période de reproduction.

```statblock
image: [[monstre.png]]
name: Ruinard
size: TG
type: Aberration
subtype: 
alignment: Non aligné
ac: 14
hp: 84
hit_dice: 8d12+32
speed: 9 m
stats: [17, 12, 18, 1, 12, 3]
saves:
  - Con: +6
skillsaves:
  - Perception: +3
damage_immunities: d'acide
condition_immunities: [[Empoisonné]]
senses: vision aveugle 18 m, Perception passive 13
languages: -
cr: 3
traits:
  - name: Sens aiguisés
    desc: "Le ruinard a l’avantage sur les tests de Sagesse (Perception).

Le ruinard effectue deux attaques : une avec sa morsure et une avec ses mandibules. Si les deux attaques réussissent sur une même créature, il peut tenter de l’engloutir.

_**Morsure**_. Attaque d’arme au corps-à-corps : +5 pour toucher, allonge 1,50 m, une cible. Touché : 13 (3d6+3) dégâts perforants.

_**Mandibule**_. Attaque d’arme au corps-à-corps : +5 pour toucher, allonge 1,50 m, une cible. Touché : 7 (1d8+3) dégâts tranchants.

_**Engloutissement**_. Si les deux attaques du ruinard réussissent sur la même créature, ce dernier peut tenter de l’engloutir. La cible doit réussir un jet de sauvegarde de Constitution DD 13. En cas de réussite, la cible réussit à résister au poison du ruinard et se sort de son emprise. En cas d’échec, elle subit l’effet paralysé et est engloutie par le ruinard qui commence à la digérer. Au début de chacun de ses tours, la cible engloutie subit 10 (3d6) points de dégâts d’acide. Elle peut ensuite retenter un jet de sauvegarde afin de contrer la paralysie. Si la cible réussit ce jet de sauvegarde, elle est alors considérée comme entravée. Elle peut tenter d’attaquer le ruinard de l’intérieur mais pour chaque attaque réussie contre le ruinard, elle subit alors immédiatement les dégâts dus à la capacité Plaies acides."
  - name: Pattes d'araignées
    desc: "Le ruinard peut escalader des surfaces difficiles et être au plafond la tête en bas sans avoir besoin d’effectuer un jet de caractéristique."
  - name: Plaies acides
    desc: "Chaque fois qu’une attaque au corps-à-corps touche le ruinard, l’attaquant subit 7 (2d6) point de dégâts d’acide. Un jet de sauvegarde de Dextérité DD 13 réussi permet de ne subir que la moitié des dégâts."
actions:
  - name: Attaques multiples
    desc: <trait-description>
  - name: Morsure
    desc: <trait-description>
  - name: Mandibule
    desc: <trait-description>
  - name: Engloutissement
    desc: <trait-description>
```
