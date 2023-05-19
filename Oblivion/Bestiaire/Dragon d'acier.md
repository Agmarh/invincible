```statblock
name: Dragon d'acier
size: G
type: Dragon
subtype: 
alignment: Chaotique Bon
ac: 17
hp: 110
hit_dice: 13d10+39
speed: 12m, fouissement 6m, vol 24m
stats: [19, 10, 17, 12, 11, 15]
saves:
  - Dex: 3
  - Con: 6
  - Sag: 3
  - Cha: 5
skillsaves:
  - Discrétion: 3
  - Perception: 6
  - Persuasion: 5
damage_immunities: feu
senses: vision aveugle 9m, vision dans le noir 36m, Perception passive 16
languages: commun, draconique
cr: 6
actions:
  - name: Attaques multiples
    desc: "Le dragon effectue trois attaques : une avec sa morsure et deux avec ses griffes."
  - name: Griffe
    desc: "Attaque d’arme au corps à corps : +7 pour toucher, allonge 1,50 m, une cible. Touché : 11 (2d6+4) dégâts tranchants."
  - name: Morsure
    desc: "Attaque d’arme au corps à corps : +7 pour toucher, allonge 3 m, une cible. Touché : 15 (2d10+4) dégâts perforants."
  - name: Souffle (Recharge 5-6)
    desc: "Le dragon utilise l’un des souffles suivants :"
  - name: Souffle de feu
    desc: "Le dragon souffle du feu sur une ligne de 12 mètres de long et 1,50 mètre de large. Les créatures sur cette ligne doivent chacune effectuer un jet de sauvegarde de Dextérité DD 14 ; elles subissent 42 (12d6) dégâts de feu en cas de jet de sauvegarde raté ou la moitié de ces dégâts seulement en cas de réussite."
  - name: Souffle soporifique
    desc: "Le dragon souffle un gaz soporifique sur un cône de 9 mètres. Les créatures dans ce cône doivent chacune réussir un jet de sauvegarde de Constitution DD 14 pour ne pas tomber inconscientes pendant 5 minutes. Une créature victime de cet effet reprend connaissance si elle subit des dégâts ou si quelqu’un consacre une action à lui faire reprendre ses esprits."
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
