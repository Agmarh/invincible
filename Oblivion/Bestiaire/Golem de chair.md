```statblock
image: [[monstre.png]]
name: Golem de chair
size: M
type: Créature artificielle
subtype: 
alignment: Neutre
ac: 9
hp: 93
hit_dice: 11d8+44
speed: 9 m
stats: [19, 9, 18, 6, 10, 5]
damage_immunities: de foudre, de poison et contondants, perforants et tranchants ingligés par des attaques non-magiques qui ne sont pas en adamantium
condition_immunities: [[Charmé]], [[Empoisonné]], Epuisé, [[Paralysé]], [[Pétrifié]], [[Terrorisé]]
senses: vision dans le noir 18 m, Perception passive 10
languages: comprend les langues de son créateur mais ne peut pas parler
cr: 5
traits:
  - name: Absorption de la foudre
    desc: "Chaque fois que le golem devrait subir des dégâts de foudre, ceux-ci ne lui sont pas infligés et il récupère, à la place, un nombre de points de vie égal aux dégâts de foudre qu'il aurait dû subir."
  - name: Armes magiques
    desc: "Les attaques d'arme du golem sont magiques."
  - name: Aversion du feu
    desc: "Si le golem subit des dégâts de feu, il subit un désavantage lors des jets d'attaque et des tests de caractéristique jusqu'à la fin de son prochain tour."
  - name: Forme immuable
    desc: "Le golem est immunisé contre les sorts et effets susceptibles d'altérer sa forme."
  - name: Fou furieux
    desc: "Chaque fois que le golem débute son tour avec 40 points de vie ou moins, lancez un d6. Sur un résultat de 6, le golem devient fou furieux. À chacun de ses tours tant qu'il est dans cet état, le golem attaque la créature la plus proche de lui dans son champ de vision. S'il n'y a aucune créature suffisamment proche pour s'en approcher et l'attaquer, le golem attaque un objet, de préférence plus petit que lui. Une fois fou furieux, le golem le reste à moins qu'il ne soit détruit ou qu'il récupère la totalité de ses points de vie. Le créateur du golem, s'il se trouve à 18 mètres ou moins du golem fou furieux, peut tenter de le calmer en s'adressant à lui d'une voix ferme et autoritaire. Le golem doit pouvoir entendre son créateur. Ce dernier doit effectuer une action pour tenter un test de Charisme (Persuasion) DD 15. En cas de test réussi, le golem se calme. S'il subit à nouveau des dégâts alors qu'il lui reste 40 points de vie ou moins, il peut de nouveau devenir fou furieux."
  - name: Résistance à la magie
    desc: "Le golem obtient un avantage lors des jets de sauvegarde contre les sorts et autres effets magiques."
actions:
  - name: Attaques multiples
    desc: <trait-description>
  - name: <trait-name>
    desc: <trait-description>
legendary_actions:
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
  - ...
bonus_actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...
tactic:
  - desc: <reaction-description>
treasure:
  - name: <reaction-name>
    desc: <reaction-description>
```
