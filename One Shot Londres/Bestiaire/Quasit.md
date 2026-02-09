```statblock
image: [[monstre.png]]
name: Quasit
size: TP
type: Fiélon
subtype: Démon, Métamorphe
alignment: Chaotique Mauvais
ac: 13
hp: 7
hit_dice: 3d4
speed: 12 m
stats: [5, 17, 10, 7, 10, 10]
skillsaves:
  - Discrétion: +5
senses: vision dans le noir 36 m, Perception passive 10
languages: abyssal, commun
cr: 1
traits:
  - name: Métamorphe
    desc: "Le quasit peut utiliser son action pour se métamorphoser en l'une des bêtes suivantes : chauve-souris (vitesse 3 m, vol 12 m), millepattes (12 m, escalade 12 m) ou crapaud (12 m, nage 12 m), ou pour reprendre sa véritable forme. Ses statistiques restent les mêmes, quelle que soit la forme adoptée, à l'exception de la vitesse indiquée. Ses objets équipés ou transportés ne sont pas transformés. Le quasit reprend sa forme véritable s'il meurt."
  - name: Résistance à la magie
    desc: "Le quasit obtient un avantage lors des jets de sauvegarde contre les sorts et autres effets magiques."
actions:
  - name: Frayeur (1/jour)
    desc: "Une créature choisie par le quasit et située à 6 mètres ou moins de lui doit réussir un jet de sauvegarde de Sagesse DD 10 pour ne pas être [[Terrorisé]] pendant 1 minute. La cible peut retenter le jet de sauvegarde à la fin de chacun de ses tours (elle subit un désavantage si le quasit est dans son champ de vision) et mettre fin à l'effet dont elle est victime en cas de réussite."
  - name: Griffe (Morsure sous forme de bête)
    desc: "Attaque d'arme au corps à corps : +4 pour toucher, allonge 1,50 m, une cible. Touché : 5 (1d4+3) dégâts perforants, et la cible doit réussir un jet de sauvegarde de Constitution DD 10 pour ne pas subir 5 (2d4) dégâts de poison et être [[Empoisonné]] pendant 1 minute. La cible peut retenter le jet de sauvegarde à la fin de chacun de ses tours et mettre fin à l'effet dont elle est victime en cas de réussite."
  - name: Invisibilité
    desc: "Le quasit devient invisible par magie jusqu'à ce qu'il attaque ou utilise sa Frayeur, ou si sa concentration est interrompue (comme s'il se concentrait sur un sort). Ses objets équipés ou transportés deviennent également invisibles."
```
