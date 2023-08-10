```statblock
image: [[monstre.png]]
name: Népharum Supérieur
size: Gig
type: Mort-vivant
subtype: Nuitant
alignment: Chaotique Mauvais
ac: 18
hp: 207
hit_dice: 18d10+108
speed: 9 m
stats: [26, 14, 22, 18, 17, 18]
saves:
  - For: +13
  - Con: +11
  - Sag: +8
skillsaves:
  - Athlétisme: +13
  - Intimidation: +14
  - Perception: +8
damage_immunities: de poison
condition_immunities: [[Charmé]], [[Empoisonné]], Epuisé, [[Paralysé]]
senses: vision aveugle 18 m, Perception passive 19
languages: abyssal, commun des profondeurs, commun
cr: 19
spells:
  - "Le Népharum peut lancer certains sorts, le DD pour résister à ces sorts est de 21."
  - à volonté: [[Ténèbres]], [[Protection contre le mal et le bien]] (limité au bien)
  - une fois entre chaque repos court (pour chaque sort): [[Jeter une malédiction]], [[Flamboiement funeste]], [[Colère des damnés]]. Ces 3 sorts sont lancés au niveau 7
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
    desc: "Attaque d’arme au corps-àcorps : +13 pour toucher, allonge 3 m, une cible. Touché : 29 (3d10+8) dégâts nécrotiques. Ces dégâts sont considérés comme magiques."
  - name: Morsure de Népharum
    desc: "Attaque d’arme au corps-à-corps : +13 pour toucher, allonge 3 m, une cible. Touché : 11 (1d6+8) dégâts perforants. Ces dégâts sont considérés comme magiques. Toute créature blessée par une morsure de népharum doit réussir un jet de sauvegarde de Constitution DD 21 ou subir l’état paralysé pendant 1d6 rounds."
legendary_actions:
  - name: Le népharum Rex peut effectuer trois actions légendaires qu’il choisit parmi celles décrites ici. Une seule action légendaire peut être choisie à la fois, et uniquement à la fin du tour d’une autre créature. Le népharum Rex récupère au début de son tour les actions légendaires déjà effectuées.
  - name: Attaque (1 action)
    desc: "Le népharum Rex peut effectuer une action attaquer."
  - name: Déplacement surnaturel (1 action)
    desc: "Le népharum Rex peut se déplacer de deux fois sa vitesse. Il n’est pas soumis aux attaques d’opportunité qui pourraient le cibler."
  - name: Magie démoniaque (2 actions)
    desc: "Le népharum peut utiliser l’un de ses pouvoirs magiques."
tactic:
  - desc: "Il arrive que le Népharum manie plutôt une hache simple et un bouclier. Dans ce cas sa CA passe à 22 et ses dégâts d’arme deviennent : Touché : 24 (4d6+10) dégâts nécrotiques."
```
