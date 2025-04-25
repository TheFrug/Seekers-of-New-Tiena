---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/5
- monster/environment/underdark
- monster/size/large
- monster/type/aberration
aliases: ["Otyugh"]
---
# Otyugh
*Source: SRD 5.2*  

## Otyugh

*Garbage-Heap Gourmand*

- **Habitat.** Underdark  
- **Treasure.** Any  

Otyughs live to eat—the more disgusting the meal, the better. They consider all non-otyughs that come within reach dishes in life's endless buffet. In dumps, sewers, polluted ruins, and similar murky depths, otyughs devour garbage, carcasses, and anything else their tentacles can cram in their expansive maws. Some creatures ply otyughs with trash to recruit them as watchful—if disgusting—guardians.

Otyughs often bury themselves amid trash heaps and observe their surroundings with their eye-studded stalk. They use glittery trash and telepathic urgings to coax creatures close, then burst from hiding, attacking with their spiny tentacles and filthy maws. Roll on or choose a result from the Otyugh Lures table to inspire how an otyugh tempts prey close.

**Otyugh Lures**

`dice: [](otyugh-xmm.md#^otyugh-lures)`

| dice: 1d4 | To Attract Potential Meals, the Otyugh... |
|-----------|-------------------------------------------|
| 1 | Disguises its tentacles with garbage puppets. |
| 2 | Sings an enticing song in Otyugh. |
| 3 | Telepathically transmits a message like "Happy good stuff here!" or "Help now! I'm too delicious?" |
| 4 | Telepathically transmits an image of a large gemstone, crooked weapon, or soggy pastry. |
^otyugh-lures

```ad-statblock
title: Otyugh
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Otyugh.webp#token)
*Large aberration, Neutral*

- **Armor Class** 14
- **Hit Points** 104 (`11d10 + 44`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|11 (+0)|19 (+4)| 6 (-2)|13 (+1)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Languages** Otyugh; telepathy 120 ft. (doesn't allow the receiving creature to respond telepathically)
- **Challenge** 5

## Actions

***Multiattack.*** The otyugh makes one Bite attack and two Tentacle attacks.

***Bite.*** *Melee Attack Roll:* `+6`, reach 5 ft. *Hit:* 12 (`2d8 + 3`) Piercing damage, and the target has the [Poisoned](rules/conditions.md#Poisoned) condition. Whenever the [Poisoned](rules/conditions.md#Poisoned) target finishes a [Long Rest](rules/variant-rules/long-rest-xphb.md), it is subjected to the following effect. *Constitution Saving Throw:* DC 15. *Failure:* The target's [Hit Point](rules/variant-rules/hit-points-xphb.md) maximum decreases by 5 (`1d10`) and doesn't return to normal until the [Poisoned](rules/conditions.md#Poisoned) condition ends on the target. *Success:* The [Poisoned](rules/conditions.md#Poisoned) condition ends.

***Tentacle.*** *Melee Attack Roll:* `+6`, reach 10 ft. *Hit:* 12 (`2d8 + 3`) Piercing damage. If the target is a Medium or smaller creature, it has the [Grappled](rules/conditions.md#Grappled) condition (escape DC 13) from one of two tentacles.

***Tentacle Slam.*** *Constitution Saving Throw:* DC 14, each creature [Grappled](rules/conditions.md#Grappled) by the otyugh. *Failure:* 16 (`3d8 + 3`) Bludgeoning damage, and the target has the [Stunned](rules/conditions.md#Stunned) condition until the start of the otyugh's next turn. *Success:* Half damage only.
```
^statblock

## Environment

underdark