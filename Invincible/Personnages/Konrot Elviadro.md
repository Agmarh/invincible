```statblock
image: [[monstre.png]]
name: Konrot Elviadro
size: M
type: Humanoïde
subtype: Tieffelin Na'saqwu
alignment: Chaotique Neutre
ac: 14
hp: 44
hit_dice: 6d8
speed: 9
stats: [8, 14, 14, 10, 12, 16]
saves:
  - Sag: 4
  - Cha: 6
skillsaves:
  - Arcanes: 3
  - Histoire: 3
  - Intimidation: 6
  - Investigation: 3
damage_resistances: poison
senses: vision dans le noir 18m, Perception passive 11
languages: commun, infernal, gobelin
spells:
  - Lanceur de sort de niveau 6, DDJS 13, bonus d'attaque +6
  - Tours de magie: Explosion occulte, Viser juste, Bouffée de poison, Illusion mineure
  - Niveau 1: Simulacre de vie, Flamboiement funeste
  - Niveau 2: Briser, Pas brumeux, Représailles infernales
  - Niveau 3 (2 emplacements) : Caresse du Vampire, Contresort
traits:
  - name: Relique
    desc: Possède le bracelet d'un seigneur de guerre, vous obtenez la maîtrise des armes de guerre et des armures intermédiaires.
  - name: Explosion insoutenable
    desc: Quand vous lancez explosion occulte, ajoutez votre modificateur de Charisme aux dégâts.
  - name: Vigueur fiélonne
    desc: Permet de lancer simulacre de vie à volonté sur vous-même sans utiliser d'emplacement de sort.
  - name: Lame assoiffée
    desc: À chaque fois que vous utilisez l'action attaquer à votre tour, vous pouvez attaquer deux fois au lieu d'une avec votre arme de pacte.
  - name: Pacte de la Lame
    desc: Créer une arme magique avec maitrise - (seigneur immortel).
  - name: Don Mage Combattant
    desc: Peut exécuter une composante somatique avec la main qui tient une arme. Peut lancer un tour de magie en action bonus si attaque pendant le tour. 
  - name: Pacte avec la mort
    desc: Si décède, jet de sauvegarde de Charisme DD 10 / 15 ou 20 suivant l'état du corps pour revenir à la vie au bout de 1d6 heures avec 1d6 PV. Vous perdez définitivement 1 point de Constitution.
  - name: Connaître l'âme
    desc: Dépenser votre action bonus afin de tenter de lire l'âme de l'humanoïde, 1 round = humeur générale, 3 rounds = état d'esprit, 5 rounds = peur ou désir caché. Si 5 rounds, DDJS Charisme 8 + Mod CHA. Concentration.
  - name: Corps et âme
    desc: Vous connaissez les tours de magie bouffée de poison et illusion mineure. Vous pouvez les lancer chacun un nombre de fois égal à votre bonus de maîtrise entre deux repos longs. Pour pouvoir lancer de nouveau ces sorts, vous devez avoir pris un repos long.
  - name: Estimation
    desc: Capable d'évaluer la valeur approximative d'un trésor.
actions:
  - name: [[Tue-Mort]]
    desc: "Attaque d'arme au corps à corps : +6 pour toucher, allonge 3 m, une cible. Touché : 7 (1d8+3) dégâts perforants."
  - ...
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
