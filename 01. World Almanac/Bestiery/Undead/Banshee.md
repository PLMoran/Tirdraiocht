```statblock
name: Banshee
image: https://www.dndbeyond.com/avatars/thumbnails/30761/972/1000/1000/638061101973584758.png
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
    desc: The banshee can magically sense the presence of creatures up to 5 miles away that aren’t undead or constructs. She knows the general direction they’re in but not their exact locations.
  - name: Incorporeal Movement
    desc: The banshee can move through other creatures and objects as if they were difficult terrain. She takes 5 (1d10) force damage if she ends her turn inside an object.
actions:
  - name: Corrupting Touch
    desc: _Melee Spell Attack:_ +4 to hit, reach 5 ft., one target. _Hit:_ 12 (3d6 + 2) necrotic damage.
    attack_bonus: 4
    damage_dice: 3d6
    damage_bonus: 2
  - name: Horrifying Visage
    desc: Each non-undead creature within 60 feet of the banshee that can see her must succeed on a DC 13 Wisdom saving throw or be frightened for 1 minute. A frightened target can repeat the saving throw at the end of each of its turns, with disadvantage if the banshee is within line of sight, ending the effect on itself on a success. If a target’s saving throw is successful or the effect ends for it, the target is immune to the banshee’s Horrifying Visage for the next 24 hours.
  - name: Wail (1/Day)
    desc: The banshee releases a mournful wail, provided that she isn’t in sunlight. This wail has no effect on constructs and undead. All other creatures within 30 feet of her that can hear her must make a DC 13 Constitution saving throw. On a failure, a creature drops to 0 hit points. On a success, a creature takes 10 (3d6) psychic damage.
```