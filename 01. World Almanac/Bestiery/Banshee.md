```statblock
name: Banshee
source: LMoP
size: Medium
type: undead
alignment: chaotic evil
ac: 12
hp: 58
hit_dice: 13d8
speed: fly 40 ft(hover)
stats:
  - 1
  - 14
  - 10
  - 12
  - 11
  - 17
skillsaves:
  - WIS: 2
  - CHA: 5
damage_vulnerabilities: ""
damage_resistances: "Acid, Fire, Lightning, Thunder; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Cold, Necrotic, Poison"
condition_immunities: "Charmed, Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained"
senses: darkvision 60 ft., passive Perception 10
languages: Common, Elvish
cr: "4"
bestiary: true
traits:
  - name: Detect Life
    desc:The banshee can magically sense the presence of creatures up to 5 miles away that aren’t undead or constructs. She knows the general direction they’re in but not their exact locations.
  - name: Incorporeal Movement
    desc: The banshee can move through other creatures and objects as if they were difficult terrain. She takes 5 (1d10) force damage if she ends her turn inside an object.
actions:
  - name: Corrupting Touch
    desc: _Melee Spell Attack:_ +4 to hit, reach 5 ft., one target. _Hit:_ 12 (3d6 + 2) necrotic damage.
    attack_bonus: 4
    damage_dice: 3d6
    damage_bonus: 2
```