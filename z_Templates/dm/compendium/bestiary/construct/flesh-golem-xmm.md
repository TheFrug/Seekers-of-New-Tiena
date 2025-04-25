---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/5
- monster/environment/any
- monster/size/medium
- monster/type/construct
aliases: ["Flesh Golem"]
---
# Flesh Golem
*Source: SRD 5.2*  

## Flesh Golem

*Dead Flesh Given New Life*

- **Habitat.** Any  
- **Treasure.** Arcana  

Flesh golems are roughly human-shaped collections of body parts bound together by misused magic or strange science. They serve their reckless creators, but many possess disjointed memories and instincts from their component parts. If wounded, these golems might go berserk and vent their confusion on anything in their sight, including their creators.

Flesh golems appear in varied forms. Roll on or choose a result from the Flesh Golem Characteristics table to inspire a flesh golem's features.

**Flesh Golem Characteristics**

`dice: [](flesh-golem-xmm.md#^flesh-golem-characteristics)`

| dice: 1d6 | The Flesh Golem Has... |
|-----------|------------------------|
| 1 | Animal parts among its humanlike pieces. |
| 2 | A disguise of makeup and heavy clothing. |
| 3 | Missing parts and exposed insides. |
| 4 | Parts serving unintended roles, like a body composed of dozens of hands. |
| 5 | Perfect features accented by beautiful stitching. |
| 6 | Visible mechanisms, bellows, and engines. |
^flesh-golem-characteristics

> [!quote] A quote from Viktra Mordenheim, Darklord of Lamordia  
> 
> The barrier between the mortal and the divine lies shattered—open is the mold for new gods. It was I who invaded the divine. Not with a spear but with a stitch. Not with my heresies but with my heart.


```ad-statblock
title: Flesh Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Flesh%20Golem.webp#token)
*Medium construct, Neutral*

- **Armor Class** 9
- **Hit Points** 127 (`15d8 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)| 9 (-1)|18 (+4)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** lightning, poison
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [exhaustion](rules/conditions.md#Exhaustion), [frightened](rules/conditions.md#Frightened), [paralyzed](rules/conditions.md#Paralyzed), [petrified](rules/conditions.md#Petrified), [poisoned](rules/conditions.md#Poisoned)
- **Languages** understands Common plus one other language but can't speak
- **Challenge** 5

## Traits

***Aversion to Fire.*** If the golem takes Fire damage, it has [Disadvantage](rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks until the end of its next turn.

***Berserk.*** Whenever the golem starts its turn [Bloodied](rules/variant-rules/bloodied-xphb.md), roll `1d6`. On a 6, the golem goes berserk. On each of its turns while berserk, the golem attacks the nearest creature it can see. If no creature is near enough to move to and attack, the golem attacks an object. Once the golem goes berserk, it remains so until it is destroyed or it is no longer [Bloodied](rules/variant-rules/bloodied-xphb.md).

The golem's creator, if within 60 feet of the berserk golem, can try to calm it by taking an action to make a DC 15 Charisma ([Persuasion](rules/skills.md#Persuasion)) check; the golem must be able to hear its creator. If this check succeeds, the golem ceases being berserk until the start of its next turn, at which point it resumes rolling for the Berserk trait again if it is still [Bloodied](rules/variant-rules/bloodied-xphb.md).

***Immutable Form.*** The golem can't shape-shift.

***Lightning Absorption.*** Whenever the golem is subjected to Lightning damage, it regains a number of [Hit Points](rules/variant-rules/hit-points-xphb.md) equal to the Lightning damage dealt.

***Magic Resistance.*** The golem has [Advantage](rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The golem makes two Slam attacks.

***Slam.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 13 (`2d8 + 4`) Bludgeoning damage plus 4 (`1d8`) Lightning damage.
```
^statblock

## Environment

any