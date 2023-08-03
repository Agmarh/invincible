```statblock
image: [[monstre.png]]
name: Fantôme
size: M
type: Mort-vivant
subtype: 
alignment: N'importe quel alignement
ac: 11
hp: 45
hit_dice: 10d8
speed: 0 m, vol 12 m
stats: [7, 13, 10, 10, 12, 17]
damage_resistances: d'acide, de feu, de foudre, de tonnerre et contondants, perforants et tranchants infligés par des attaques non-magiques
damage_immunities: de froid, nécrotiques et de poison
condition_immunities: A terre, [[Charmé]], [[Empoigné]], [[Empoisonné]], Epuisé, [[Entravé]], [[Paralysé]], [[Pétrifié]], [[Terrorisé]]
senses: vision dans le noir 18 m, Perception passive 11
languages: toutes les langues qu'il connaissait de son vivant
cr: 4
traits:
  - name: Déplacement intangible
    desc: "Le fantôme peut traverser créatures et objets en les considérant comme un terrain difficile. Il subit 5 (1d10) dégâts de force s'il termine son tour à l'intérieur d'un objet."
  - name: Vision éthérée
    desc: "Le fantôme peut voir jusqu'à 18 mètres dans le plan Éthéré depuis le plan Matériel et vice versa."
actions:
  - name: Contact flétrissant
    desc: "Attaque d'arme au corps à corps : +5 pour toucher, allonge 1,50 m, une cible. Touché : 17 (4d6+3) dégâts nécrotiques."
  - name: Forme éthérée
    desc: "Le fantôme entre dans le plan Éthéré depuis le plan Matériel, ou vice versa. Il est visible sur le plan Matériel quand il est dans la Frontière éthérée et vice-versa, mais il ne peut pas affecter et ne peut pas être affecté par quoi que ce soit provenant de l'autre plan."
  - name: Possession (Recharge 6)
    desc: "Un humanoïde ciblé situé dans le champ de vision du fantôme et à 1,50 mètre ou moins de lui doit réussir un jet de sauvegarde de Charisme DD 13 pour ne pas être possédé par le mort-vivant ; le fantôme disparaît alors et la cible est [[Neutralisé]] et perd le contrôle de son corps. Le fantôme contrôle désormais ce corps, mais la cible reste consciente. Il est alors impossible de cibler le fantôme avec une attaque, un sort ou un autre effet, à l'exception de ceux qui renvoient les morts-vivants. Il conserve son alignement, son Intelligence, sa Sagesse, son Charisme et ses immunités contre les états spéciaux [[Charmé]] et [[Terrorisé]]. Pour le reste, il utilise les statistiques de la cible possédée mais n'a pas accès à ses connaissances, à ses aptitudes de classe ni à ses maîtrises.  
La possession prend fin si le corps physique tombe à 0 point de vie, si le fantôme y met un terme par une action bonus ou s'il est renvoyé ou obligé d'abandonner le corps grâce à un effet produit par un sort de [_dissipation du mal et du bien_](https://5e-drs.fr/grimoire/dissipation-du-mal-et-du-bien/), par exemple. Lorsque la possession prend fin, le fantôme réapparaît dans un emplacement inoccupé situé à 1,50 mètre ou moins du corps. La cible est immunisée contre le pouvoir de possession de ce fantôme pendant les 24 heures qui suivent son [jet de sauvegarde](https://5e-drs.fr/utiliser-les-caracteristiques/#jets-de-sauvegarde) réussi ou l'interruption de la possession."
  - name: Visage terrifiant
    desc: <trait-description>
```
