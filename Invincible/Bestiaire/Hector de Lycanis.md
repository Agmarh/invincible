```statblock
image: [[monstre.png]]
name: Hector de Lycanis
size: M
type: Humanoïde
subtype: Humain
alignment: Neutre Mauvais
ac: 18 (demi-plate +1)
hp: 112
hit_dice: 15d8+45
speed: 9m (12m sous forme de loup)
stats: [18, 15, 16, 10, 14, 15]
saves:
  - For: 7
  - Dex: 5
  - Con: 6
skillsaves:
  - Athlétisme: 10
  - Intimidation: 5
  - Discrétion: 5
  - Perception: 5
damage_immunities: contondants, perforants et tranchants infligés par des attaques non-magiques d'armes qui ne sont pas en argent
senses: Perception passive 15
languages: commun
cr: 7
traits:
  - name: Brave
    desc: "Hector obtient un avantage lors des jets de sauvegarde effectués pour ne pas être [[Terrorisé]]."
  - name: Brutal
    desc: "Une arme de corps à corps inflige un dé supplémentaire de ses dégâts quand Hector réussit une attaque en la maniant (inclus dans l'attaque)."
  - name: Métamorphe
    desc: "Hector peut utiliser son action pour se métamorphoser en hybride d'humanoïde et de loup, en loup, ou pour reprendre sa véritable forme d'humanoïde. Ses statistiques restent les mêmes, quelle que soit la forme adoptée mais au moment ou il se transforme pour la première fois en forme hybride ou en loup ce jour-là, il récupère 4d8+4 points de vie. Ses objets équipés ou transportés ne sont pas transformés à l'exception de son armure magique qui s'adapte à sa nouvelle forme. Le loup-garou reprend sa forme véritable s'il meurt."
  - name: Odorat et ouüe aiguisés
    desc: "Hector est avantagé lors des tests de Sagesse (Perception) basés sur l'odorat ou l'ouïe."
actions:
  - name: Attaques multiples
    desc: "Sous forme humanoïde Hector effectue deux attaques au corps à corps ou deux attaques à distance. Sous forme hybride Hector effectue deux attaques à l'épée (ou de griffe s'il est désarmé) et une avec sa morsure."
  - name: Epée à 2 mains (forme humanoïde ou hybride uniquement)
    desc: "Attaque d'arme au corps à corps ou à distance : +8 pour toucher, allonge 1,50 m, une créature. Touché : 14 (3d6+4) dégâts tranchants + 1d6 dégâts nécrotiques pendant 3 rounds (voir saignemort)."
  - name: Morsure (forme hybride ou de loup)
    desc: <trait-description>
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
