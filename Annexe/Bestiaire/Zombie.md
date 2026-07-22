```statblock
image: [[monstre.png]]
name: Zombie
size: M
type: Mort-vivant
subtype: 
alignment: Neutre Mauvais
ac: 8
hp: 22
hit_dice: 3d8+9
speed: 6 m
stats: [13, 6, 16, 3, 6, 5]
saves:
  - Sag: 0
damage_immunities: de poison
condition_immunities: [[Empoisonné]]
senses: vision dans le noir 18 m, Perception passive 8
languages: celles qu'il connaissait de son vivant
cr: 1/4
traits:
  - name: Robustesse de la non-vie
    desc: "Si des dégâts réduisent à 0 les points de vie du zombi, celui-ci doit effectuer un jet de sauvegarde de Constitution DD 5 + les dégâts subis, à moins que ces dégâts soient de type radiant ou infligés par un coup critique. En cas de réussite, le zombi tombe à 1 point de vie à la place."
actions:
  - name: Coup
    desc: "Attaque d'arme au corps à corps : +3 pour toucher, allonge 1,50 m, une cible. Touché : 4 (1d6+1) dégâts contondants."
```
