---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/2
- monster/environment/underdark
- monster/size/large
- monster/type/ooze
aliases: ["Gelatinous Cube"]
---
# Gelatinous Cube
*Source: SRD 5.2 and the Free Rules (2024)*  

## Gelatinous Cube

*Dungeon-Scouring Block of Ooze*

- **Habitat.** Underdark  
- **Treasure.** Any  

Quivering masses of acidic goo, gelatinous cubes wobble through narrow caverns and dungeons, engulfing anything in their paths. These Oozes are naturally transparent, making them difficult to see while they're stationary. Creatures and objects that become stuck within these slimes are gradually dissolved. Undigested detritus sometimes floats within a gelatinous cube, hinting at its past meals. Roll on or choose a result from the Gelatinous Cube Debris table to inspire a gelatinous cube's contents.

**Gelatinous Cube Debris**

`dice: [](gelatinous-cube-xmm.md#^gelatinous-cube-debris)`

| dice: 1d6 | Floating in the Gelatinous Cube Is A... |
|-----------|-----------------------------------------|
| 1 | Chest or recently trapped mimic. |
| 2 | Collection of bubbles or rocks resembling eyes. |
| 3 | Key to a nearby door or coffer. |
| 4 | Remarkable weapon in need of repair. |
| 5 | Skeleton belonging to a famous adventurer. |
| 6 | Tablet bearing a mysterious message. |
^gelatinous-cube-debris

```ad-statblock
title: Gelatinous Cube
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Gelatinous%20Cube.webp#token)
*Large ooze, Unaligned*

- **Armor Class** 6
- **Hit Points** 63 (`6d10 + 30`)
- **Speed** 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)| 3 (-4)|20 (+5)| 1 (-5)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft., passive Perception 8
- **Damage Immunities** acid
- **Condition Immunities** [blinded](rules/conditions.md#Blinded), [charmed](rules/conditions.md#Charmed), [deafened](rules/conditions.md#Deafened), [exhaustion](rules/conditions.md#Exhaustion), [frightened](rules/conditions.md#Frightened), [prone](rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 2

## Traits

***Ooze Cube.*** The cube fills its entire space and is transparent. Other creatures can enter that space, but a creature that does so is subjected to the cube's Engulf and has [Disadvantage](rules/variant-rules/disadvantage-xphb.md) on the saving throw.

Creatures inside the cube have [Total Cover](rules/variant-rules/cover-xphb.md), and the cube can hold one Large creature or up to four Medium or Small creatures inside itself at a time.

As an action, a creature within 5 feet of the cube can pull a creature or an object out of the cube by succeeding on a DC 12 Strength ([Athletics](rules/skills.md#Athletics)) check, and the puller takes 10 (`3d6`) Acid damage.

***Transparent.*** Even when the cube is in plain sight, a creature must succeed on a DC 15 Wisdom ([Perception](rules/skills.md#Perception)) check to notice the cube if the creature hasn't witnessed the cube move or otherwise act.

## Actions

***Pseudopod.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 12 (`3d6 + 2`) Acid damage.

***Engulf.*** The cube moves up to its [Speed](rules/variant-rules/speed-xphb.md) without provoking Opportunity Attacks. The cube can move through the spaces of Large or smaller creatures if it has room inside itself to contain them (see the Ooze [Cube](rules/variant-rules/cube-area-of-effect-xphb.md) trait). *Dexterity Saving Throw:* DC 12, each creature whose space the cube enters for the first time during this move. *Failure:* 10 (`3d6`) Acid damage, and the target is engulfed. An engulfed target is suffocating, can't cast spells with a Verbal component, has the [Restrained](rules/conditions.md#Restrained) condition, and takes 10 (`3d6`) Acid damage at the start of each of the cube's turns. When the cube moves, the engulfed target moves with it. An engulfed target can try to escape by taking an action to make a DC 12 Strength ([Athletics](rules/skills.md#Athletics)) check. On a successful check, the target escapes and enters the nearest unoccupied space. *Success:* Half damage, and the target moves to an unoccupied space within 5 feet of the cube. If there is no unoccupied space, the target fails the save instead.
```
^statblock

## Environment

underdark