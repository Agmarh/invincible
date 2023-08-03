Les éféemères sont l’incarnation des rêves poétiques, emplis de pureté ou d’innocence. Elles ont l’apparence de fées noires et sont dotées d’élégantes ailes ténébreuses. Seule leur chevelure est blanche. Les éféemères portent une grande sarbacane d’ivoire. Ces nuitants respirent le bien-être et n’ont qu’un désir : inspirer aux autres créatures vivantes le même genre d’émotions qui les a créées. Selon leur nature, elles utilisent leurs pouvoirs pour générer l’apaisement, provoquer le rire, exalter la beauté d’une personne, etc. Cette volonté peut aller jusqu’au sacrifice : c’est l’Apothéose, un rituel au cours duquel l’éféemère fait cadeau de sa brève existence pour provoquer l’émotion recherchée.

```statblock
image: [[monstre.png]]
name: Eféemère
size: P
type: Fée
subtype: 
alignment: Toujours Bon
ac: 17 
hp: 35
hit_dice: 10d6
speed: 0 m, vol 9 m
stats: [7, 18, 11, 14, 16, 19]
skillsaves:
  - Perception: +7
  - Représentation: +8
  - Discrétion: +8
damage_immunities: d'acide et de poison
condition_immunities: [[Empoisonné]]
senses: vision dans le noir 36 m, Perception passive 17
languages: 
cr: 3
traits:
  - name: Vision dans les ténèbres
    desc: "Les nuitants voient dans les ténèbres de n’importe quel type, y compris magique, sur une distance de 36 m."
  - name: Résistance à la magie
    desc: "Ils obtiennent un avantage sur tous les jets de sauvegarde afin de résister aux sorts d’illusion."
  - name: Chevelure parfumée
    desc: "Le parfum de la chevelure florale des éféemères produit à la fois les effets des sorts charme-personne et apaisement des émotions (jet de sauvegarde DD 17 pour y résister), de façon permanente, dans un rayon de 6 m autour de la créature."
  - name: Apothéose
    desc: "Pour le bien d’une tierce personne, et seulement dans ce but, une éféemère peut consumer son pouvoir d’un seul coup et faire d’un rêve une réalité. En pratique, l’effet est identique à un souhait que l’éféemère formule en fonction de sa personnalité. Par exemple, une éféemère, incarnation d’un rêve apaisant, pourra choisir de mourir en Apothéose pour apporter à quelqu’un la paix de l’âme (dissiper une malédiction...) ou du corps (guérir une blessure critique...). Quel que soit le résultat, l’éféemère se consume définitivement au cours de cette Apothéose."
  - name: Engendrer une fée
    desc: "Comme les autres nuitants, les éféemères ne peuvent pas se reproduire. Elles peuvent néanmoins engendrer une fée, une fois par an, en plantant une graine unique issue de leur chevelure de fleur. La graine germe en sept jours, produisant une cosse d’or. Jetez 1d6 pour déterminer quelle fée apparaît alors : 1-2 une dryade, 3-4 un esprit follet, 5-6 un satyre. Ces créatures possèdent un aspect légèrement modifié, comme tout Oblivien « ordinaire »."
  - name: Sarbacane
    desc: "Cet objet de nature magique est considéré comme une arme +2. Il sert à projeter des fléchettes ou des poudres, selon que l’éféemère souhaite affecter une ou plusieurs personnes."
  - name: Pouvoirs magiques
    desc: "L'éféemère est capable de lancer les sorts suivants : charme-personne, lumières dansantes, détection du bien et du mal, invisibilité, image majeure, non détection. Une éféemère sur dix peut incanter métamorphose suprême. Quand l’un de ces sorts est lancé, elle doit attendre d’avoir effectué un repos long avant de pouvoir le relancer."
actions:
  - name: Attaques multiples
    desc: <trait-description>
  - name: Sarbacane - confusion de l'esprit
    desc: <trait-description>
  - name: <trait-name>
    desc: <trait-description>
  - name: <trait-name>
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
