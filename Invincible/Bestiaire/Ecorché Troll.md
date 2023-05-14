```statblock
image: [[Troll de pierre.jpg]]
name: Ecorché Troll
size: G
type: Mort-Vivant
subtype: 
alignment: Neutre Mauvais
ac: 15 (armure naturelle)
hp: 85
hit_dice: 9d10+36
speed: 9m
stats: [18, 10, 18, 5, 7, 7]
saves:
  - Con: 6
damage_resistances: feu, psychiques
damage_immunities: poison
condition_immunities: [[Empoisonné]], charmé, [[Terrorisé]]
senses: vision dans le noir 19m, Perception passive 8
languages: ne parle pas, ne comprend aucune langue
cr: 4
traits:
  - name: Régénération
    desc: "L'écorché troll récupère 5 points de vie au début de son tour. S'il subit des dégâts d'acide ou de feu, ce trait ne fonctionne pas au début du prochain tour du troll. L'écorché troll meurt uniquement s'il commence son tour avec 0 point de vie et ne se régénère pas."
  - name: Robustesse de la non-vie
    desc: "Si des dégâts réduisent à 0 les points de vie de l'écorché, celui-ci doit effectuer un jet de sauvegarde de Constitution DD 5 + les dégâts subis, à moins que ces dégâts de soient de type radiants ou infligés par un coup critique. En cas de réussite, l'écorché tombe à 1 point de vie à la place."
actions:
  - name: Attaques multiples
    desc: "Le troll effectue deux attaques avec ses griffes."
  - name: <trait-name>
    desc: <trait-description>
legendary_actions:
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
  - ...
bonus_actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...
tactic:
  - desc: <reaction-description>
treasure:
  - name: <reaction-name>
    desc: <reaction-description>
```
