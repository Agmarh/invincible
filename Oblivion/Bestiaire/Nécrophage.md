```statblock
image: [[monstre.png]]
name: Nécrophage
size: M
type: Mort-vivant
subtype: 
alignment: Neutre Mauvais
ac: 14
hp: 45
hit_dice: 6d8+18
speed: 9 m
stats: [15, 14, 16, 10, 13, 15]
skillsaves:
  - Discrétion: +4
  - Perception: +3
damage_resistances: nécrotiques et contondants, perforants et tranchants infligés par des attaques non-magiques qui ne sont pas en argent
damage_immunities: de poison
condition_immunities: [[Empoisonné]], Epuisé
senses: vision dans le noir 18 m, Perception passive 13
languages: celles qu'il connaissait de son vivant
cr: 3
traits:
  - name: Sensibilité à la lumière du soleil
    desc: "Le nécrophage subit un désavantage lors des jets d'attaque et des tests de Sagesse (Perception) basés sur la vue lorsqu'il est exposé à la lumière du soleil."
actions:
  - name: Attaques multiples
    desc: "Le nécrophage effectue deux attaques à l'épée longue ou deux attaques à l'arc long. Il peut utiliser son _Absorption de vie_ à la place d'une attaque à l'épée longue."
  - name: Absorption de vie
    desc: "Attaque d'arme au corps à corps : +4 pour toucher, allonge 1,50 m, une créature. Touché : 5 (1d6+2) dégâts nécrotiques. La cible doit réussir un jet de sauvegarde de Constitution DD 13 pour ne pas voir son total maximum de points de vie réduit d'un montant égal aux dégâts subis. Cette réduction persiste jusqu'au moment où la créature termine une période de repos long. La cible meurt si cet effet réduit à 0 son total maximum de points de vie. Un humanoïde tué par cette attaque se relève 24 heures plus tard sous forme de zombi contrôlé par le nécrophage, à moins qu'il ne soit ramené à la vie ou que son corps soit détruit. Le nécrophage ne peut avoir plus de douze zombis sous son contrôle en même temps."
  - name: Arc long
    desc: "Attaque d'arme à distance : +4 pour toucher, portée 45/180 m, une cible. Touché : 6 (1d8+2) dégâts perforants."
  - name: Epée longue
    desc: "Attaque d'arme au corps à corps : +4 pour toucher, allonge 1,50 m, une cible. Touché : 6 (1d8+2) dégâts tranchants ou 7 (1d10+2) dégâts tranchants si elle est maniée à deux mains."
```
