```statblock
image: [[monstre.png]]
name: Dominia
size: M
type: Mort-Vivant
subtype: 
alignment: Neutre Mauvais
ac: 15 (bracelets de défense et Dextérité)
hp: 82
hit_dice: 11d8+33
speed: 9
stats: [16, 16, 16, 11, 10, 15]
saves:
  - Dex: 6
  - Sag: 3
skillsaves:
  - Discrétion: 6
  - Perception: 3
damage_resistances: nécrotiques ; contondants, perforants et tranchants infligés par des attaques non-magiques
senses: vision dans le noir 18 m, Perception passive 13
languages: commun, draconique
cr: 6
traits:
  - name: Régénération
    desc: Dominia récupère 10 points de vie au début de son tour s'il lui reste au moins 1 point de vie.
  - name: Aura de faiblesse
    desc: Cette aura nécromantique affaiblit les créatures vivantes dans un rayon de 6 mètres autour de Dominia. À chaque tour, tout adversaire dans la zone doit réussir un jet de sauvegarde de Constitution DD 13 ou subir un désavantage à toutes ses actions basées sur la Force. Cela comprend les attaques qui utilisent le modificateur de Force.
actions:
  - name: Attaques multiples
    desc: "Dominia effectue deux attaques à l'épée longue et une de plus avec son fouet d'os."
  - name: Epée longue
    desc: "Attaque d'arme au corps à corps : +7 pour toucher, allonge 1,50 m, une créature. Touché : 8 (1d8+4) dégâts tranchants."
  - name: Fouet d'os
    desc: "Attaque d'arme au corps à corps : +7 pour toucher, allonge 3 m, une cible. Touché : 6 (1d6+3) dégâts perforants et jet de sauvegarde de Constitution DD 13 ou étourdi jusqu'au prochain tour de Dominia."
tactic:
  - desc: "Dominia combat jusqu'à la mort. Grâce aux pouvoirs de Lytochronox, elle se croit invincible. Lorsqu'elle atteint 0 pv, elle se transforme en goule."
treasure:
  - name: Epée longue +1
  - name: Bracelets de défense
  - name: Fouet d'os
    desc: "Il perd son pouvoir entre d'autres mains, mais il inflige 1d6 + modificateur de Dextérités dégâts perforants. Portée 3 mètres. Arme martiale."
  - name: Croc du dragon
    desc: "Dominia garde toujours sur elle le ‘Croc du Dragon', une dague dont la lame est une griffe de Lytochronox. Sa garde est en métal noir et la lame est une griffe décolorée. Le poignard est seulement utilisé pour le rituel de création des écorchés, mais elle le garde précieusement. Il s'agit d'une véritable relique. L'arme ne donne aucun bonus, mais elle est considérée comme magique. Toutefois, si elle est utilisée contre le dragon (sous n'importe quelle forme, même un « émissaire » du scénario 5), elle ignore la résistance de la créature."
```
