---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/30
- monster/environment/urban
- monster/size/gargantuan
- monster/type/monstrosity/titan
aliases: ["Tarrasque"]
---
# Tarrasque
*Source: SRD 5.2*  

## Tarrasque

*The Shape of Calamity*

- **Habitat.** Urban  
- **Treasure.** None  

Among the most devastating creatures in existence, the tarrasque is an engine of catastrophe and a ruiner of nations. A terror of massive size and overwhelming might, this primeval destroyer survives from the earliest epochs of the Material Plane, when it served as a weapon of immortal forces. Since then, the tarrasque has slumbered in secret, rising every few ages to usher in eras of destruction.

The tarrasque is a bipedal, prehistoric Monstrosity that stands over seventy feet tall. Bristling with horns and spikes, its spiny carapace deflects harm and can reflect magical attacks.

The tarrasque is a creature of tireless rage. It lashes out at any creature that catches its attention, thrashing with claws and its mighty tail while swallowing smaller beings whole. It seems to take instinctual offense at the works of lesser beings, venting its rage at buildings, bridges, ships, and monuments. The larger a structure or foe is, the greater the tarrasque's wrath.

It is a mystery what—if anything—calms the tarrasque, but eventually it returns to its slumber, leaving the world irrevocably changed. While the tarrasque might be halted by incredible opposition, its threat can never be wiped from the multiverse. Whenever the tarrasque is defeated, another tarrasque awakes somewhere else on the Material Plane.

Few things survive the tarrasque's rampages, and reports of the monster's devastation are often contradictory, incomplete, or beyond belief. In cases where it leaves no survivors, its calamities might initially be blamed on evil dragons or magical disasters, but the tarrasque frequently leaves behind some unmistakable indication of its passage. Roll on or choose a result from the Tarrasque Evidence table to inspire what marks the monster's rampages.

**Tarrasque Evidence**

`dice: [](tarrasque-xmm.md#^tarrasque-evidence)`

| dice: 1d4 | Amid Destruction, the Tarrasque Leaves... |
|-----------|-------------------------------------------|
| 1 | Evidence of a magic spell reflected back on its caster, like Ice Knife or Melf's Acid Arrow. |
| 2 | Massive footprints or claw marks. |
| 3 | A russet scale the size of a knight's shield. |
| 4 | A shattered mountain or diverted river. |
^tarrasque-evidence

```ad-statblock
title: Tarrasque
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Tarrasque.webp#token)
*Gargantuan monstrosity (titan), Unaligned*

- **Armor Class** 25
- **Hit Points** 697 (`34d20 + 340`)
- **Speed** 60 ft., burrow 40 ft., climb 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|11 (+0)|30 (+10)| 3 (-4)|11 (+0)|11 (+0)|

- **Proficiency Bonus** +9
- **Saving Throws** Dexterity +9, Intelligence +5, Wisdom +9, Charisma +9
- **Skills** Perception +9
- **Senses** blindsight 120 ft., passive Perception 19
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [deafened](rules/conditions.md#Deafened), [frightened](rules/conditions.md#Frightened), [paralyzed](rules/conditions.md#Paralyzed), [poisoned](rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 30

## Traits

***Legendary Resistance (6/Day).*** If the tarrasque fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The tarrasque has [Advantage](rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Reflective Carapace.*** If the tarrasque is targeted by a [Magic Missile](compendium/spells/magic-missile-xphb.md) spell or a spell that requires a ranged attack roll, roll `1d6`. On a 1-5, the tarrasque is unaffected. On a 6, the tarrasque is unaffected and reflects the spell, turning the caster into the target.

***Siege Monster.*** The tarrasque deals double damage to objects and structures.

## Actions

***Multiattack.*** The tarrasque makes one Bite attack and three other attacks, using Claw or Tail in any combination.

***Bite.*** *Melee Attack Roll:* `+19`, reach 15 ft. *Hit:* 36 (`4d12 + 10`) Piercing damage, and the target has the [Grappled](rules/conditions.md#Grappled) condition (escape DC 20). Until the grapple ends, the target has the [Restrained](rules/conditions.md#Restrained) condition and can't teleport.

***Claw.*** *Melee Attack Roll:* `+19`, reach 15 ft. *Hit:* 28 (`4d8 + 10`) Slashing damage.

***Tail.*** *Melee Attack Roll:* `+19`, reach 30 ft. *Hit:* 23 (`3d8 + 10`) Bludgeoning damage. If the target is a Huge or smaller creature, it has the [Prone](rules/conditions.md#Prone) condition.

***Thunderous Bellow (Recharge 5-6).*** *Constitution Saving Throw:* DC 27, each creature and each object that isn't being worn or carried in a 150-foot [Cone](rules/variant-rules/cone-area-of-effect-xphb.md). *Failure:* 78 (`12d12`) Thunder damage, and the target has the [Deafened](rules/conditions.md#Deafened) and [Frightened](rules/conditions.md#Frightened) conditions until the end of its next turn. *Success:* Half damage only.

## Bonus Actions

***Swallow.*** *Strength Saving Throw:* DC 27, one Large or smaller creature [Grappled](rules/conditions.md#Grappled) by the tarrasque (it can have up to six creatures swallowed at a time). *Failure:* The target is swallowed, and the [Grappled](rules/conditions.md#Grappled) condition ends. A swallowed creature has the [Blinded](rules/conditions.md#Blinded) and [Restrained](rules/conditions.md#Restrained) conditions and can't teleport, it has [Total Cover](rules/variant-rules/cover-xphb.md) against attacks and other effects outside the tarrasque, and it takes 56 (`16d6`) Acid damage at the start of each of the tarrasque's turns.

If the tarrasque takes 60 damage or more on a single turn from a creature inside it, the tarrasque must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the tarrasque and has the [Prone](rules/conditions.md#Prone) condition. If the tarrasque dies, any swallowed creature no longer has the [Restrained](rules/conditions.md#Restrained) condition and can escape from the corpse using 20 feet of movement, exiting [Prone](rules/conditions.md#Prone).

## Legendary Actions

***Onslaught.*** The tarrasque moves up to half its [Speed](rules/variant-rules/speed-xphb.md), and it makes one Claw or Tail attack.

***World-Shaking Movement.*** The tarrasque moves up to its [Speed](rules/variant-rules/speed-xphb.md). At the end of this movement, the tarrasque creates an instantaneous shock wave in a 60-foot <span title="Player's Handbook (2024)">Emanation</span> originating from itself. Creatures in that area lose [Concentration](rules/conditions.md#Concentration) and, if Medium or smaller, have the [Prone](rules/conditions.md#Prone) condition. The tarrasque can't take this action again until the start of its next turn.
```
^statblock

## Environment

urban