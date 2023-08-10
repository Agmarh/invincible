```statblock
image: [[monstre.png]]
name: Ravageur
size: G
type: Fiélon
subtype: 
alignment: Loyal Mauvais
ac: 13
hp: 142
hit_dice: 15d10+60
speed: 12 m, vol 12 m
stats: [18, 16, 18, 13, 14, 16]
saves:
  - Int: +5
  - Sag: +6
  - Cha: +7
skillsaves:
  - Perspicacité: +6
  - Supercherie: +7
damage_resistances: contondants, perforants et tranchants inflgiés par des attaques non-magiques qui ne sont pas en argent et de froid
damage_immunities: de feu et de poison
senses: vision dans le noir 36 m, Perception passive 12
languages: commun, infernal
cr: 9
traits:
  - name: Résistance à la magie
    desc: "Le ravageur obtient un avantage lors des jets de sauvegarde contre les sorts et autres effets magiques."
  - name: Pouvoirs du ravageur
    desc: "Le ravageur peut utiliser les sorts suivant à leur niveau minimal : soins des blessures, blessure, détection du mal et du bien, détection de la magie, détection des pensées, voir l’invisible, compréhension des langues. Il peut lancer chacun de ces sorts une fois entre chaque repos court ou long."
  - name: Insondable
    desc: "Le ravageur est en permanence sous l’effet du sort esprit impénétrable. Cet effet ne peut être détecté avec le sort détection de la magie."
actions:
  - name: Attaques multiples
    desc: "Le ravageur effectue trois attaques : deux avec ses griffes et une avec son dard."
  - name: Dard
    desc: "Attaque d’arme au corps-à-corps : +8 pour toucher, allonge 3 m, une cible. Touché : 13 (2d8+4) dégâts perforants et 17 (5d6) dégâts de poison, et la cible doit réussir un jet de sauvegarde de Constitution DD 14 pour ne pas être empoisonnée pendant 1 minute. La cible peut retenter le jet de sauvegarde à la fin de chacun de ses tours et mettre fin à l’effet dont elle est victime en cas de réussite"
  - name: Griffes
    desc: "Attaque d’arme au corps-à-corps : +8 pour toucher, allonge 3 m, une cible. Touché : 8 (1d8+4) dégâts tranchants."
```
