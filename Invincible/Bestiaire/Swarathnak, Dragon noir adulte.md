```statblock
image: [[monstre.png]]
name: Swarathnak, Dragon noir adulte
size: TG
type: Dragon
subtype: 
alignment: Chaotique Mauvais
ac: 19
hp: 195
hit_dice: 17d12+85
speed: 12m, nage 12m, vol 24m
stats: [23, 14, 21, 14, 13, 17]
saves:
  - Dex: +7
  - Con: +10
  - Sag: +6
  - Cha: +8
skillsaves:
  - Discrétion: +7
  - Perception: +11
damage_immunities: d'acide
senses: vision aveugle 18m, vision dans le noir 36m, Perception passive 21
languages: commun, draconique
cr: 14
traits:
  - name: Amphibie
    desc: "Le dragon peut respirer l'air et l'eau"
  - name: Résistance légendaire (3/jour)
    desc: "Le dragon peut remplacer l'échec d'un de ses jets de sauvegarde par une réussite."
actions:
  - name: Attaques multiples
    desc: "Le dragon peut utiliser sa Présence terrifiante. Il effectue ensuite trois attaques : une avec sa morsure et deux avec ses griffes."
  - name: Morsure
    desc: "Attaque d'arme au corps à corps : 11 (1d20+11) pour toucher, allonge 3 m, une cible. Touché : 17 (2d10+6) dégâts perforants plus 4 (1d8) dégâts d'acide."
  - name: Griffe
    desc: "Attaque d'arme au corps à corps : 11 (1d20+11) pour toucher, allonge 1,50 m, une cible. Touché : 13 (2d6+6) dégâts tranchants."
  - name: Queue
    desc: "Attaque d'arme au corps à corps : 11 (1d20+11) pour toucher, allonge 4,50 m, une cible. Touché : 15 (2d8+6) dégâts contondants."
  - name: Présence terrifiante
    desc: "Les créatures choisies par le dragon, situées à 36 mètres ou moins de lui et conscientes de sa présence, doivent chacune réussir un jet de sauvegarde de Sagesse DD 16 pour ne pas être terrorisées pendant 1 minute. Une créature peut retenter le jet de sauvegarde à la fin de chacun de ses tours et mettre fin à l'effet dont elle est victime en cas de réussite. Si le jet de sauvegarde d'une créature est réussi ou si l'effet dont elle est victime prend fin, elle est immunisée contre la présence terrifiante du dragon pendant 24 heures."
  - name: Souffle d'acide (Recharge 5-6)
    desc: "Le dragon souffle de l'acide sur une ligne de 18 mètres de long et 1,50 mètre de large. Les créatures sur cette ligne doivent chacune effectuer un jet de sauvegarde de Dextérité DD 18 ; elles subissent 54 (12d8) dégâts d'acide en cas d'échec ou la moitié de ces dégâts seulement en cas de réussite."
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
