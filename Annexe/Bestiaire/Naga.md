Naga est une créature à l’apparence moitié humanoïde, moitié serpentine. Son corps entier semble fait de chitine noire et figée, et il ne se meut que parce que les parties mobiles sont constituées d’anneaux. Son visage est figé dans un rictus terrifiant.

```statblock
image: [[monstre.png]]
name: Naga
size: G
type: Créature monstrueuse
subtype: 
alignment: Chaotique Mauvais
ac: 15
hp: 75
hit_dice: 10d10+20
speed: 12 m
stats: [18, 17, 14, 16, 15, 16]
saves:
  - Dex: +6
  - Con: +5
  - Sag: +5
  - Cha: +6
damage_immunities: de poison
condition_immunities: [[Charmé]], [[Empoisonné]]
senses: vision dans le noir 18 m, Perception passive 12
languages: -
cr: 8
spells:
  - "Le naga est un lanceur de sorts de niveau 10. Sa caractéristique d'incantation est l'Intelligence (DD du jet de sauvegarde contre les sorts 14, +6 pour toucher avec les attaques de sort) et seules les composantes verbales sont nécessaires pour lancer ses sorts."
  - Tours de magie: [[Illusion mineure]], [[Main du mage]], [[Rayon de givre]]
  - 1er niveau (4 emplacements): [[Charme-personne]], [[Détection de la magie]], [[Sommeil]]
  - 2e niveau (3 emplacements): [[Détection des pensées]], [[Immobiliser un humanoïde]]
  - 3e niveau (3 emplacements): [[Éclair]], [[Respiration aquatique]]
  - 4e niveau (3 emplacements): [[Flétrissement]], [[Porte dimensionnelle]]
  - 5e niveau (2 emplacements): [[Dominer un humanoïde]]
traits:
  - name: Reconstitution
    desc: "S'il meurt, le naga revient à la vie avec la totalité de ses points de vie au bout de 1d6 jours. Seul un sort de souhait peut empêcher le fonctionnement de ce trait."
  - name: Résistance à la magie
    desc: "Naga obtient un avantage lors des jets de sauvegarde contre les sorts et autres effets magiques."
  - name: Pouvoirs du ravageur
    desc: "Naga peut utiliser les sorts suivants à leur niveau minimal : soins des blessures, blessure, détection du mal et du bien, détection de la magie, détection des pensées, voir l’invisible, compréhension des langues. Il peut lancer chacun de ces sorts une fois entre chaque repos court ou long."
  - name: Insondable
    desc: "Naga est en permanence sous l’effet du sort esprit impénétrable. Cet effet ne peut être détecté avec le sort détection de la magie."
actions:
  - name: Morsure
    desc: "Attaque d'arme au corps à corps : +7 pour toucher, allonge 3 m, une créature. Touché : 7 (1d6+4) dégâts perforants et la cible doit effectuer un jet de sauvegarde de Constitution DD 13 ; elle subit 31 (7d8) dégâts de poison en cas de jet de sauvegarde raté ou la moitié de ces dégâts seulement en cas de réussite."
```
