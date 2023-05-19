```statblock
name: Gobelin
size: P
type: Humanoïde
subtype: Gobelin
alignment: Neutre Mauvais
ac: 15
hp: 7
hit_dice: 2d6
speed: 9
stats: [8, 14, 10, 10, 8, 8]
skillsaves:
  - Discrétion: 6
senses: vision dans le noir 18m, Perception passive 9
languages: commun, gobelin
cr: 1/4
traits:
  - name: Fuite agile
    desc: "Le gobelin peut effectuer l'action se désengager ou se cacher par une action bonus à chacun de ses tours."
actions:
  - name: Arc court
    desc: "Attaque d'arme à distance : +4 pour toucher, portée 24/96 m, une cible.  
_Touché_ : 5 (1d6+2) dégâts perforants."
  - ...
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
