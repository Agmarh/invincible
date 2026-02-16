```statblock
image: [[monstre.png]]
name: Rejeton d'Akyishigal
size: M
type: Fiélon
subtype: Démon
alignment: Chaotique Mauvais
ac: 15
hp: 119
hit_dice: 14d8+56
speed: 9 m, escalade 4,50 m
stats: [15, 13, 19, 10, 11, 12]
saves:
  - Dex: +4
damage_immunities: de poison
condition_immunities: [[Empoisonné]]
senses: vision dans le noir 18 m, Perception passive 10
languages: infernal
cr: 5
traits:
  - name: Contrôle de la vermine
    desc: "Les rejetons d'Akyishigal peuvent donner des ordres à des bêtes de Très Petite taille d'une Intelligence de 2 ou moins, qui se trouvent dans un rayon de 9 mètres et ne sont pas contrôlées par magie. La vermine obéit aux ordres du rejeton au mieux de ses capacités sans se soucier de sa propre sécurité."
  - name: Expectoration de nuées (recharge 5-6)
    desc: "Un rejeton peut cracher une [[Nuée d'insectes]]. Cette nuée est entièrement sous son contrôle. Elle persiste pendant une minute ou jusqu'à ce qu'elle soit détruite."
actions:
  - name: Attaques multiples
    desc: "Un rejeton porte une attaque de morsure et deux de dard."
  - name: Morsure
    desc: "Attaque d'arme au corps à corps : +5 pour toucher, allonge 1,50 m, une cible. Touché : 7 (1d10 + 2) dégâts perforants."
  - name: Dard
    desc: "Attaque d'arme au corps à corps : +5 pour toucher, allonge 1,50 m, une cible. Touché : 11 (2d8 + 2) dégâts perforants plus 5 (1d10) dégâts de poison, et la cible doit réussir un jet de sauvegarde de Constitution DD 15 ou être [[Empoisonné]] pour 1d6 rounds."
```
