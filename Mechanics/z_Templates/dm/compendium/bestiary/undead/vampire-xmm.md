---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/13
- monster/environment/underdark
- monster/environment/urban
- monster/size/small-or-medium
- monster/type/undead
aliases: ["Vampire"]
---
# Vampire
*Source: SRD 5.2*  

Vampires are terrifying hunters and manipulators. They use their powers to shape-shift and bend other creatures' wills as they terrorize and feed on populations over generations.

## Vampires

*Blood-Sucking Lords of the Night*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Vampires disguise their accursed, immortal natures, passing as mortals to feed on the blood of the living. While the youngest vampires might be little more than bloodthirsty servants of their creators, the eldest possess incredible cunning and control over supernatural forces of the night.

Undead vampires lie dormant during the day, retreating to resting places hidden from foes and the sun's searing rays. Roll on or choose a result from the Vampire Resting Places table to inspire a vampire's grim sanctuary.

**Vampire Resting Places**

`dice: [](vampire-xmm.md#^vampire-resting-places)`

| dice: 1d6 | The Vampire's Resting Place Is... |
|-----------|-----------------------------------|
| 1 | Among the roots of a dead tree. |
| 2 | At the bottom of a stagnant pool. |
| 3 | A coffin filled with grave dirt. |
| 4 | A large pot full of blood or vinegar. |
| 5 | A space accessible only by shape-shifting. |
| 6 | Within a statue or suit of armor. |
^vampire-resting-places

### Vampire Lairs

Vampires and vampire umbral lords create sanctuaries apart from the living, whether hidden in cosmopolitan cities or sequestered in ruins where they dwelled in life.

> [!quote] A quote from Astarion, Vampire Spawn  
> 
> Darling, you are simply delicious...


## Statblock

```ad-statblock
title: Vampire
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Vampire.webp#token)
*Small or Medium undead, Lawful Evil*

- **Armor Class** 16
- **Hit Points** 195 (`23d8 + 92`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Constitution +9, Wisdom +7, Charisma +9
- **Skills** Perception +7, Stealth +9
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** necrotic
- **Languages** Common plus two other languages
- **Challenge** 13

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the vampire fails a saving throw, it can choose to succeed instead.

***Misty Escape.*** If the vampire drops to 0 [Hit Points](rules/variant-rules/hit-points-xphb.md) outside its resting place, the vampire uses Shape-Shift to become mist (no action required). If it can't use Shape-Shift, it is destroyed.

While it has 0 [Hit Points](rules/variant-rules/hit-points-xphb.md) in mist form, it can't return to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it returns to its vampire form and has the [Paralyzed](rules/conditions.md#Paralyzed) condition until it regains any [Hit Points](rules/variant-rules/hit-points-xphb.md), and it regains 1 [Hit Point](rules/variant-rules/hit-points-xphb.md) after spending 1 hour there.

***Spider Climb.*** The vampire can climb difficult surfaces, including along ceilings, without needing to make an ability check.

***Vampire Weakness.*** The vampire has these weaknesses:

- **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.  
- **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.  
- **Stake to the Heart.** If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the [Incapacitated](rules/conditions.md#Incapacitated) condition in its resting place, the vampire has the [Paralyzed](rules/conditions.md#Paralyzed) condition until the weapon is removed.  
- **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has [Disadvantage](rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks.  

***Charm (Recharge 5-6).*** The vampire casts [Charm Person](compendium/spells/charm-person-xphb.md), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 17), and the duration is 24 hours. The Charmed target is a willing recipient of the vampire's Bite, the damage of which doesn't end the spell. When the spell ends, the target is unaware it was Charmed by the vampire.


***Beguile.*** The vampire casts [Command](compendium/spells/command-xphb.md), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 17). The vampire can't take this action again until the start of its next turn.


## Actions

***Multiattack (Vampire Form Only).*** The vampire makes two Grave Strike attacks and uses Bite.

***Grave Strike (Vampire Form Only).*** *Melee Attack Roll:* `+9`, reach 5 ft. *Hit:* 8 (`1d8 + 4`) Bludgeoning damage plus 7 (`2d6`) Necrotic damage. If the target is a Large or smaller creature, it has the [Grappled](rules/conditions.md#Grappled) condition (escape DC 14) from one of two hands.

***Bite (Bat or Vampire Form Only).*** *Constitution Saving Throw:* DC 17, one creature within 5 feet that is willing or that has the [Grappled](rules/conditions.md#Grappled), [Incapacitated](rules/conditions.md#Incapacitated), or [Restrained](rules/conditions.md#Restrained) condition. *Failure:* 6 (`1d4 + 4`) Piercing damage plus 13 (`3d8`) Necrotic damage. The target's [Hit Point](rules/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains [Hit Points](rules/variant-rules/hit-points-xphb.md) equal to that amount. A Humanoid reduced to 0 [Hit Points](rules/variant-rules/hit-points-xphb.md) by this damage and then buried rises the following sunset as a [Vampire Spawn](compendium/bestiary/undead/vampire-spawn-xmm.md) under the vampire's control.

## Bonus Actions

***Shape-Shift.*** If the vampire isn't in sunlight or running water, it shape-shifts into a Tiny bat ([Speed](rules/variant-rules/speed-xphb.md) 5 ft., [Fly Speed](rules/variant-rules/fly-speed-xphb.md) 30 ft.) or a Medium cloud of mist ([Speed](rules/variant-rules/speed-xphb.md) 5 ft., [Fly Speed](rules/variant-rules/fly-speed-xphb.md) 20 ft. [hover]), or it returns to its vampire form. Anything it is wearing transforms with it.

While in bat form, the vampire can't speak. Its game statistics, other than its size and [Speed](rules/variant-rules/speed-xphb.md), are unchanged.

While in mist form, the vampire can't take any actions, speak, or manipulate objects. It is weightless and can enter an enemy's space and stop there. If air can pass through a space, the mist can do so, but it can't pass through liquid. It has [Resistance](rules/variant-rules/resistance-xphb.md) to all damage, except the damage it takes from sunlight.

## Legendary Actions

***Deathless Strike.*** The vampire moves up to half its [Speed](rules/variant-rules/speed-xphb.md), and it makes one Grave Strike attack.
```
^statblock

## Environment

underdark, urban