```statblock
name: Gulguthra
source: 5e SRD
size: Large
type: aberration
subtype: ""
alignment: neutral
ac: 14
hp: 114
hit_dice: 12d10 + 48
speed: 30 ft.
stats:
  - 16
  - 11
  - 19
  - 6
  - 13
  - 6
saves:
  - constitution: 7
damage_vulnerabilities: ""
damage_resistances: "Poison"
damage_immunities: ""
condition_immunities: ""
senses: darkvision 120 ft., passive Perception 11
languages: Otyugh
cr: "5"
bestiary: true
traits:
  - name: Limited Telepathy
    desc: The otyugh can magically transmit simple messages and images to any creature within 120 ft. of it that can understand a language. This form of telepathy doesn't allow the receiving creature to telepathically respond.
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The otyugh makes three attacks: one with its bite and two with its tentacles."
    attack_bonus: 0
  - name: Bite
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12 (2d8 + 3) piercing damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw against disease or become poisoned until the disease is cured. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by 5 (1d10) on a failure. The disease is cured on a success. The target dies if the disease reduces its hit point maximum to 0. This reduction to the target's hit point maximum lasts until the disease is cured."
    attack_bonus: 6
    damage_dice: 2d8
    damage_bonus: 3
  - name: Tentacle
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 7 (1d8 + 3) bludgeoning damage plus 4 (1d8) piercing damage. If the target is Medium or smaller, it is grappled (escape DC 13) and restrained until the grapple ends. The otyugh has two tentacles, each of which can grapple one target."
    attack_bonus: 6
    damage_dice: 1d8
    damage_bonus: 3
  - name: Tentacle Slam
    desc: The otyugh slams creatures grappled by it into each other or a solid surface. Each creature must succeed on a DC 14 Constitution saving throw or take 10 (2d6 + 3) bludgeoning damage and be stunned until the end of the otyugh's next turn. On a successful save, the target takes half the bludgeoning damage and isn't stunned.
    attack_bonus: 0
  - name: Corpse Chuck
    desc: "Ranged Weapon Attack: +3 to hit, reach 30 ft., one target. Hit: 4 (1d8 + 0) bludgeoning damage plus 10 (2d8) piercing damage. The Gulguthra throws a pestilent piece of a corpse at a target. Target must make a CON save (DC 13) or take 2d6 poison damage."
    attack_bonus: 3
    damage_dice: 1d8
    damage_bonus: 0
```
