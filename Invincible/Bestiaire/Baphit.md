```statblock
image: [[monstre.png]]
name: Baphit
size: M
type: Humanoïde
subtype: 
alignment: Loyal Neutre
ac: 10
hp: 60
hit_dice: 8d8+24
speed: 9
stats: [19, 10, 16, 5, 7, 7]
senses: vision dans le noir 18 m, Perception passive 8
languages: commun
cr: 3
traits:
  - name: Régénération
    desc: Récupère 5 PV au début de son tour s'il lui reste au moins 1 PV.
  - name: Rage
    desc: Si Dominia est blessée et en danger, entre en rage. Obtient un avantage aux tests de Force et Sauvegarde de Force. Quand il utilise une arme de CAC, il gagne +3 au jet de dégâts. Il devient résistant aux dégâts contondants, perforants et tranchants.
actions:
  - name: Attaques multiples.
    desc: Effectue deux attaques à mains nues.
  - name: Mains nues
    desc: "Attaque d'arme au corps à corps : +6 pour toucher, allonge 1,50 m, une cible. Touché : 6 (1d4+4) dégâts contondants."
  - name: Javeline
    desc: +6 pour toucher, 9/36m, 7 (1d6+4) dégâts perforants.
tactic:
  - desc: "Combat jusqu'à la mort si la vie de Dominia est en jeu, sinon prend la fuite s'il lui reste 15 PV."
```
