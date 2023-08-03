Chelios se présente comme un monstre à la chitine noire. Il ne possède pas d’yeux, pas de bouche, et son corps évoque celui une araignée géante. Mais au lieu de la tête de l’araignée, on trouve un buste humanoïde dont les bras sont terminés par d’immenses griffes tranchantes. Son visage lisse et long achève de parfaire cette apparence étrange.

```statblock
image: [[monstre.png]]
name: Chelios
size: G
type: Aberration
subtype: 
alignment: Chaotique Mauvais
ac: 16
hp: 105
hit_dice: 14d10+27
speed: 12 m, nage 12 m
stats: [20, 16, 14, 13, 14, 10]
saves:
  - For: +8
  - Dex: +6
  - Sag: +5
skillsaves:
  - Athlétisme: +8
  - Discrétion: +6
  - Perception: +5
damage_immunities: feu et de poison
condition_immunities: [[Empoisonné]]
senses: vision dnas le noir 36 m, Perception passive 15
languages: commun, gnome, abyssal, télépathie 36 m
cr: 6
traits:
  - name: Résistance à la magie
    desc: "Chelios obtient un avantage lors des jets de sauvegarde contre les sorts et autres effets magiques."
  - name: Vue du diable
    desc: "Les ténèbres magiques ne bloquent pas la vision dans le noir de Chelios."
  - name: Pouvoirs du ravageur
    desc: "Chelios peut utiliser les sorts suivants à leur niveau minimal : soins des blessures, blessure, détection du mal et du bien, détection de la magie, détection des pensées, voir l’invisible, compréhension des langues. Il peut lancer chacun de ces sorts une fois entre chaque repos court ou long."
  - name: Insondable
    desc: "Chelios est en permanence sous l’effet du sort esprit impénétrable. Cet effet ne peut être détecté avec le sort détection de la magie."
  - name: Perception de la magie
    desc: "Chelios perçoit la magie à volonté sur un rayon de 36 m. L’effet est le même que pour le sort détection de la magie même si cette capacité n’est pas magique en soi."
  - name: Amphibie
    desc: "Chelios peut respirer à l’air libre comme sous l’eau."
  - name: Pattes d'araignées
    desc: "Chelios peut escalader des surfaces difficiles et être au plafond la tête en bas sans avoir besoin d’effectuer un jet de caractéristique."
actions:
  - name: Attaques multiples
    desc: "Chelios effectue trois attaques de griffes. S’il en réussit deux sur la même cible, il peut utiliser sa capacité Absorption magique."
  - name: Griffes
    desc: "Attaque d’arme au corps-à-corps : +8 pour toucher, allonge 1,5 m, une cible. Touché : 13 (2d6+5) dégâts perforants. S’il réussit deux attaques contre la même cible, elle est alors empoignée."
  - name: Absorption magique
    desc: "Si Chelios empoigne une cible et que cette dernière est un lanceur de sorts, son visage s’ouvre en deux et commence à absorber la magie se trouvant en elle. La cible doit immédiatement effectuer un jet de sauvegarde de Constitution DD 14 ou perdre son plus haut emplacement de sort non encore dépensé. Au début de chacun de ses tours, tant qu’elle reste empoignée, la cible doit effectuer un nouveau jet de sauvegarde ou perdre un autre emplacement de sort. Si la cible n’a plus aucun emplacement de sort disponible pour absorption, elle subit un niveau de fatigue."
```
