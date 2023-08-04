```statblock
image: [[monstre.png]]
name: Népharum Rex
size: Gig
type: Mort-vivant
subtype: Nuitant
alignment: Chaotique Mauvais
ac: 20
hp: 222
hit_dice: 12d20+96
speed: 9 m
stats: [30, 14, 26, 18, 17, 18]
saves:
  - For: +16
  - Con: +14
  - Sag: +9
skillsaves:
  - Athlétisme: +16
  - Intimidation: +10
  - Perception: +9
damage_immunities: de poison
condition_immunities: [[Charmé]], [[Empoisonné]], Epuisé, [[Paralysé]]
senses: vision aveugle 18 m, Perception passive 19
languages: abyssal, commun des profondeurs, commun
cr: 19
spells:
  - "Le Népharum peut lancer certains sorts, le DD pour résister à ces sorts est de 24."
  - à volonté: [[Ténèbres]], [[Protection contre le mal et le bien]] (limité au bien)
  - une fois entre chaque repos court (pour chaque sort): [[Jeter une malédiction]], [[Flamboiement funeste]], [[Colère des damnés]]. Ces 3 sorts sont lancés au niveau 8
traits:
  - name: Résistance légendaire (3/jour)
    desc: "Le népharum peut remplacer l’échec d’un de ses jets de sauvegarde par une réussite."
  - name: Aura de terreur
    desc: "Toute créature à moins de 3 m d’un népharum doit réussir un jet de sauvegarde de Sagesse (DD 18) ou subir immédiatement l’effet terrorisé. Les créatures immunisées à cet état obtiennent un avantage sur leur jet de sauvegarde mais subissent tout de même l’effet en cas d’échec."
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
  - desc: "Il arrive que le népharum manie plutôt une hache simple et un bouclier. Dans ce cas sa CA passe à 19 et ses dégâts d’arme deviennent : Touché : 16 (2d8+7) dégâts nécrotiques."
```