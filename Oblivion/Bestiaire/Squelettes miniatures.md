```statblock
image: [[monstre.png]]
name: Squelettes miniatures
size: M
type: Nuée
subtype: composée de morts-vivants de taille P
alignment: Loyal Mauvais
ac: 13
hp: 45
hit_dice: 6d10+12
speed: 9 m
stats: [10, 14, 15, 6, 8, 5]
damage_vulnerabilities: contondants
damage_immunities: de poison
condition_immunities: [[Empoisonné]], Epuisé
senses: vision dans le noir 18 m, Perception passive 9
languages: -
cr: 1/4
traits:
  - name: PV
    desc: "La nuée possède 50 PV. Chaque fois que ses points de vie sont réduits de 10, les dégâts de chaque attaque sont réduits de 1 (minimum 1)."
  - name: Attaque
    desc: "Toutes les créatures présentes dans le même espace que la nuée subissent une attaque, indépendamment du nombre d’attaques total des squelettes."
actions:
  - name: Griffes
    desc: "Attaque d'arme au corps à corps : +4 pour toucher, allonge 1,50 m, une cible. Touché : 5 (1d6+2) dégâts perforants."
```
