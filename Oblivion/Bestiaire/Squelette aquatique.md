```statblock
image: [[monstre.png]]
name: Squelette aquatique
size: G
type: Mort-vivant
subtype: 
alignment: Neutre Mauvais
ac: 12
hp: 45
hit_dice: 6d10+18
speed: 12 m
stats: [19, 11, 15, 6, 8, 5]
damage_vulnerabilities: contondants
damage_immunities: de poison
condition_immunities: [[Empoisonné]], [[Épuisé]]
senses: vision dans le noir 18 m, Perception passive 13
languages: -
cr: 8
traits:
  - name: Petit dormeur
    desc: "Quand l'hydre dort, une de ses têtes au moins reste éveillée."
  - name: Retenir son souffle
    desc: "L'hydre peut retenir son souffle pendant 1 heure."
  - name: Tête multiples
    desc: "L'hydre a cinq têtes. Tant qu'il lui reste plus d'une tête, l'hydre obtient un avantage lors des jets de sauvegarde effectués pour ne pas être assourdie, aveuglée, charmée, étourdie, inconsciente ou terrorisée. Chaque fois que l'hydre subit 25 dégâts ou plus lors d'un même tour, une de ses têtes meurt. Si toutes ses têtes meurent, l'hydre meurt également. À la fin de son tour, deux têtes repoussent pour chacune des têtes mortes lors du dernier tour, à moins qu'elle n'ait subit des dégâts de feu depuis son dernier tour. L'hydre récupère 10 points de vie pour chaque nouvelle tête repoussée de cette façon."
  - name: Têtes réactives
    desc: "Pour chaque tête que possède l'hydre au-delà de la première, elle dispose d'une réaction supplémentaire qu'elle peut utiliser pour effectuer des attaques d'opportunité uniquement."
actions:
  - name: Attaques multiples
    desc: "L'hydre effectue autant d'attaques de morsure qu'elle possède de têtes."
  - name: Morsure
    desc: "Attaque d'arme au corps à corps : +8 pour toucher, allonge 3 m, une cible. Touché : 10 (1d10+5) dégâts perforants."
```
