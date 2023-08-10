```statblock
image: [[monstre.png]]
name: Tyrannosaure
size: TG
type: Bête
subtype: Dinosaure
alignment: Non aligné
ac: 13
hp: 136
hit_dice: 13d12+52
speed: 15 m
stats: [25, 10, 19, 2, 12, 9]
skillsaves:
  - Perception: +4
senses: Perception passive 14
languages: -
cr: 8
actions:
  - name: Attaques multiples
    desc: "Le tyrannosaure effectue deux attaques : une avec sa morsure et une avec sa queue. Il ne peut pas effectuer ces deux attaques contre la même cible.

_**Morsure**_. _Attaque d'arme au corps à corps_ : +10 pour toucher, allonge 3 m, une cible.  
_Touché_ : 33 (4d12+7) dégâts perforants. La cible est [_empoignée_](https://5e-drs.fr/gerer-la-sante-du-personnage/#empoigne) (évasion DD 17) si elle est de taille M ou plus petite. Elle est [_entravée_](https://5e-drs.fr/gerer-la-sante-du-personnage/#entrave) tant qu'elle est [_empoignée_](https://5e-drs.fr/gerer-la-sante-du-personnage/#empoigne) et le tyrannosaure ne peut pas mordre une autre créature.

_**Queue**_. _Attaque d'arme au corps à corps_ : +10 pour toucher, allonge 3 m, une cible.  
_Touché_ : 20 (3d8+7) dégâts contondants."
  - name: Morsure
    desc: <trait-description>
  - name: <trait-name>
    desc: <trait-description>
```
