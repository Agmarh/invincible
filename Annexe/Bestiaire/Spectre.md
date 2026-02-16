```statblock
image: [[monstre.png]]
name: Spectre
size: M
type: Mort-vivant
subtype: 
alignment: Chaotique Mauvais
ac: 12
hp: 22
hit_dice: 5d8
speed: 0 m, vol 15 m
stats: [1, 14, 11, 10, 10, 11]
damage_resistances: d'acide, de feu, de foudre, de froid et contondants, perforants et tranchants infligés par des attaques non-magiques
damage_immunities: nécrotiques et de poison
condition_immunities: A terre, [[Charmé]], [[Empoigné]], [[Empoisonné]], [[Entravé]], Epuisé, Inconscient, [[Paralysé]], [[Pétrifié]]
senses: vision dans le noir 18 m, Perception passive 10
languages: comprend toutes les langues qu'il connaissait de son vivant mais ne peut pas parler
cr: 1
traits:
  - name: Déplacement intangible
    desc: "Le spectre peut traverser créatures et objets en les considérant comme un terrain difficile. Il subit 5 (1d10) dégâts de force s'il termine son tour à l'intérieur d'un objet."
  - name: Sensibilité à la lumière du soleil
    desc: Le spectre subit un désavantage lors des jets d'attaque et des tests de Sagesse (Perception) basés sur la vue lorsqu'il est exposé à la lumière du soleil."
actions:
  - name: Absorption de vie
    desc: "Attaque d'arme au corps à corps : +4 pour toucher, allonge 1,50 m, une créature. Touché : 10 (3d6) dégâts nécrotiques. La cible doit réussir un jet de sauvegarde de Constitution DD 10 pour ne pas voir son total maximum de points de vie réduit d'un montant égal aux dégâts subis. Cette réduction persiste jusqu'au moment où la créature termine une période de repos long. La cible meurt si cet effet réduit à 0 son total maximum de points de vie."
```
