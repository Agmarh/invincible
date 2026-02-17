```statblock
name: Golem de fer inférieur
size: G
type: Créature artificielle
subtype: 
alignment: Non-alignée
ac: 17 (armure naturelle)
hp: 178
hit_dice: 17d10+85
speed: 9 m
stats: [22, 9, 20, 3, 11, 1]
damage_resistances: contondants, perforants et tranchants infligés par des attaques non-magiques qui ne sont pas en adamantium
damage_immunities: de poison, psychiques
condition_immunities: [[Charmé]], [[Empoisonné]], [[Épuisé]], [[Paralysé]], [[Pétrifié]], [[Terrorisé]]
senses: vision dans le noir 36 m, Perception passive 10
languages: comprend les langues de son créateur mais ne peut pas parler
cr: 10
traits:
  - name: Armes magiques
    desc: "Les attaques d’arme du golem sont magiques."
  - name: Forme immuable
    desc: "Le golem est immunisé contre les sorts et effets susceptibles d’altérer sa forme."
  - name: Résistance à la magie
    desc: "Le golem obtient un avantage lors des jets de sauvegarde contre les sorts et autres effets magiques."
  - name: Point faible
    desc: "Si la matrice est retirée, le Golem cesse de fonctionner. Jet de force DD 20 pour la retirer de son socle."
actions:
  - name: Attaques multiples
    desc: "Le golem effectue deux attaques de coup."
  - name: Coup
    desc: "Attaque d’arme au corps à corps : +10 pour toucher, allonge 1,50 m, une cible. Touché : 13 (2d6+6) dégâts contondants."
  - name: Lenteur (Recharge 5-6)
    desc: "Le golem cible une ou plusieurs créatures situées dans son champ de vision à 3 mètres ou moins de lui. Les cibles doivent chacune effectuer un jet de sauvegarde de Sagesse DD 17 contre cette magie. En cas de jet de sauvegarde raté, une cible ne peut plus effectuer de réaction, sa vitesse est réduite de moitié et elle ne peut pas effectuer plus d’une attaque lors de son tour. De plus, la cible peut effectuer soit une action, soit une action bonus lors de son tour, mais pas les deux. Ces effets durent 1 minute. Une cible peut retenter le jet de sauvegarde à la fin de chacun de ses tours et mettre fin à l’effet dont elle est victime en cas de réussite."
```
