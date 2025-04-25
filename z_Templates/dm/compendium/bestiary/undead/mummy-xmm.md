---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/3
- monster/environment/desert
- monster/environment/swamp
- monster/size/small-or-medium
- monster/type/undead
aliases: ["Mummy"]
---
# Mummy
*Source: SRD 5.2*  

Common mummies are the remains of priests, nobles, or champions of faith that underwent magical burial rites. Some are preserved through processes using linen wrappings or clay, but others are preserved by peat bogs, ice, magic, or other means.

Roll on or choose a result from the Mummy Resurrections table to determine why a mummy has returned from the dead.

**Mummy Resurrections**

`dice: [](mummy-xmm.md#^mummy-resurrections)`

| dice: 1d8 | The Mummy Reanimates To... |
|-----------|----------------------------|
| 1 | Defend a holy site it was created to protect. |
| 2 | Obey the summons of a mummy lord. |
| 3 | Oppose an enemy who has returned to life. |
| 4 | Protect its descendants from an ancient threat. |
| 5 | Punish the progeny of those who cursed it. |
| 6 | Reclaim treasures robbed from its crypt. |
| 7 | Serve whoever speaks the prayer on its tomb. |
| 8 | Slay anyone who sets eyes on it. |
^mummy-resurrections

> [!quote]  
> 
> Rule 7: Before opening a sarcophagus, light a torch.

## Mummies

*Deathless Ancients with Ageless Ambitions*

- **Habitat.** Desert, Swamp  
- **Treasure.** Relics  

Mysterious rites and mighty faith can tie spirits to their corpses, binding them to their remains for all time. Should their resting places be violated, these beings, known as mummies, reanimate their deteriorating bodies to restore the sanctity of their tombs and punish those who disturbed their rest.

Mummies pursue those who offend them, typically mortals who desecrate their resting places, steal their burial treasures, or defile sites tied to their faith. With undying rage, these ancient corpses go to extreme lengths to avenge themselves and restore what they need to find peace.

A mummy might look frail, but its body possesses supernatural strength, and its gaze can strike fear in the bravest hearts. Those who escape a mummy's grasp might find themselves subject to a terrible curse. Victims of a mummy's curse gradually wither, their bodies rotting away until they're reduced to dust. This curse can be healed only by the [Remove Curse](compendium/spells/remove-curse-xphb.md) spell or similar magic.

## Statblock

```ad-statblock
title: Mummy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Mummy.webp#token)
*Small or Medium undead, Lawful Evil*

- **Armor Class** 11
- **Hit Points** 58 (`9d8 + 18`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 8 (-1)|15 (+2)| 6 (-2)|12 (+1)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +3
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Vulnerabilities** fire
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [exhaustion](rules/conditions.md#Exhaustion), [frightened](rules/conditions.md#Frightened), [paralyzed](rules/conditions.md#Paralyzed), [poisoned](rules/conditions.md#Poisoned)
- **Languages** Common plus two other languages
- **Challenge** 3

## Actions

***Multiattack.*** The mummy makes two Rotting Fist attacks and uses Dreadful Glare.

***Rotting Fist.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 8 (`1d10 + 3`) Bludgeoning damage plus 10 (`3d6`) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain [Hit Points](rules/variant-rules/hit-points-xphb.md), its [Hit Point](rules/variant-rules/hit-points-xphb.md) maximum doesn't return to normal when finishing a [Long Rest](rules/variant-rules/long-rest-xphb.md), and its [Hit Point](rules/variant-rules/hit-points-xphb.md) maximum decreases by 10 (`3d6`) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 [Hit Points](rules/variant-rules/hit-points-xphb.md) by this attack.

***Dreadful Glare.*** *Wisdom Saving Throw:* DC 11, one creature the mummy can see within 60 feet. *Failure:* The target has the [Frightened](rules/conditions.md#Frightened) condition until the end of the mummy's next turn. *Success:* The target is immune to this mummy's Dreadful Glare for 24 hours.
```
^statblock

## Environment

desert, swamp