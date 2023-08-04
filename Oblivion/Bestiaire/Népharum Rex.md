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
    desc: "Attaque d’arme au corps-àcorps : +16 pour toucher, allonge 3 m, une cible. Touché : 29 (3d12+10) dégâts nécrotiques. Ces dégâts sont considérés comme magiques."
  - name: Morsure de Népharum
    desc: "Attaque d’arme au corps-à-corps : +16 pour toucher, allonge 3 m, une cible. Touché : 13 (1d6+10) dégâts perforants. Ces dégâts sont considérés comme magiques. Toute créature blessée par une morsure de népharum doit réussir un jet de sauvegarde de Constitution DD 24 ou subir l’état paralysé pendant 1d6 rounds."
legendary_actions:
  - name: Le népharum Rex peut effectuer trois actions légendaires qu’il choisit parmi celles décrites ici. Une seule action légendaire peut être choisie à la fois, et uniquement à la fin du tour d’une autre créature. Le népharum Rex récupère au début de son tour les actions légendaires déjà effectuées.
  - name: Attaque (1 action)
    desc: "Le népharum Rex peut effectuer une action attaquer."
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
tactic:
  - desc: "Il arrive que le Népharum manie plutôt une hache simple et un bouclier. Dans ce cas sa CA passe à 22 et ses dégâts d’arme deviennent : Touché : 24 (4d6+10) dégâts nécrotiques."
```