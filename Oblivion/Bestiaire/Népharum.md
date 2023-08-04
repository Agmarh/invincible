Surnommés « les maîtres des chaînes », les redoutables népharums incarnent les rêves d’angoisse et symbolisent la souffrance prolongée d’une façon générale. De loin, leur aspect fait d’abord penser à celui des goules ghûraghastas. Comme elles, ils disposent de six hautes pattes recourbées encadrant une énorme colonne vertébrale horizontale, se redressant à l’avant en un torse humanoïde surmonté d’un crâne aux orbites vides.

Mais de près, les népharums révèlent toute leur terrifiante ampleur. Leurs os ténébreux comme du charbon luisent tels de l’oniriôm pur et emportent à plus de trois mètres de haut un torse de chair noire, couturé de piercings métalliques et de crochets cruels. Quant à leur crâne sombre, orné de clous ou bardé de fil de fer, il s'ouvre sur deux orbites vides scintillant d’une diabolique intelligence.

Experts en maniement d’armes et d’instruments de torture, les népharums en transportent toujours sur eux. Les népharums ont également la capacité d’engendrer une ghûraghasta en déposant un embryon noir dans la carcasse de leur victime. Pour cela, on les considère généralement comme les pères de cette race.

```statblock
image: [[monstre.png]]
name: Népharum
size: G
type: Mort-vivant
subtype: Nuitant
alignment: Chaotique Mauvais
ac: 12
hp: 199
hit_dice: 19d10+95
speed: 9 m
stats: [24, 14, 20, 18, 17, 15]
saves:
  - For: +11
  - Con: +9
  - Sag: +7
skillsaves:
  - Athlétisme: +11
  - Intimidation: +6
  - Perception: +7
damage_immunities: de poison
condition_immunities: [[Charmé]], [[Empoisonné]], Epuisé, [[Paralysé]]
senses: vision aveugle 18 m, Perception passive 17
languages: abyssal, commun des profondeurs, commun
cr: 12
spells:
  - "Le Népharum peut lancer certains sorts, le DD pour résister à ces sorts est de 20."
  - à volonté: [[Ténèbres]], [[Protection contre le mal et le bien]] (limité au bien)
  - une fois entre chaque repos court (pour chaque sort): [[Jeter une malédiction]], [[Flamboiement funeste]], [[Colère des damnés]]. Ces 3 sorts sont lancés au niveau 6
traits:
  - name: Vision dans les ténèbres
    desc: "Les nuitants voient dans les ténèbres de n’importe quel type, y compris magique, sur une distance de 36 m."
  - name: Résistance à la magie
    desc: "Ils obtiennent un avantage sur tous les jets de sauvegarde afin de résister aux sorts d’illusion."
  - name: Résistance légendaire (3/jour)
    desc: "Le népharum peut remplacer l’échec d’un de ses jets de sauvegarde par une réussite."
  - name: Aura de terreur
    desc: "Toute créature à moins de 3 m d’un népharum doit réussir un jet de sauvegarde de Sagesse (DD 15) ou subir immédiatement l’effet terrorisé. Les créatures immunisées à cet état obtiennent un avantage sur leur jet de sauvegarde mais subissent tout de même l’effet en cas d’échec."
  - name: Engendrer une ghûraghasta
    desc: "Généralement, un népharum torture et dévore ceux qu’il tue. Parfois, il dépose dans leur cadavre un embryon noir unique et l’ensemble se transforme abominablement pour ressusciter sous la forme d’une ghûraghasta. Ce processus prend 1d4 jours. À son terme, ils deviennent une nouvelle et immonde ghûraghasta. Un sort de protection contre le mal et le bien lancé sur le cadavre avant la fin de sa transformation permet d’enrayer le processus."
  - name: Traquer la peur
    desc: "Le népharum est capable de ressentir la peur de ses proies. Il a l’avantage à tous les tests de Sagesse (Survie) effectués afin de les pister. Les paladins ne peuvent être traqués de la sorte."
actions:
  - name: Attaques multiples
    desc: "Le Népharum peut effectuer trois attaques de hache et une attaque de morsure avec une action attaquer."
  - name: Hache de Népharum
    desc: "Attaque d’arme au corps-àcorps : +12 pour toucher, allonge 3 m, une cible. Touché : 20 (2d12+7) dégâts nécrotiques. Ces dégâts sont considérés comme magiques."
  - name: Morsure de Népharum
    desc: "Attaque d’arme au corps-à-corps : +12 pour toucher, allonge 3 m, une cible. Touché : 10 (1d6+7) dégâts perforants. Ces dégâts sont considérés comme magiques. Toute créature blessée par une morsure de népharum doit réussir un jet de sauvegarde de Constitution DD 20 ou subir l’état paralysé pendant 1d6 rounds."
tactic:
  - desc: <reaction-description>
```
