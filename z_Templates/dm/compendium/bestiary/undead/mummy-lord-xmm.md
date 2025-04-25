---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/15
- monster/environment/desert
- monster/environment/swamp
- monster/size/small-or-medium
- monster/type/undead
aliases: ["Mummy Lord"]
---
# Mummy Lord
*Source: SRD 5.2*  

Those desperate to escape death sometimes make terrible bargains with wicked deities. Devoting their hearts to evil forces, these villains gain power over death and a cursed immortality that binds their minds and spirits within a desiccated corpse. Freed from mortal concerns, these mummy lords pursue their obsessions across ages.

Most mummy lords linger amid the ruins of ancient palaces or temples where they once held sway. Their age-old faith and ties to deathly forces grant them fearful magic, which they use to sow ruin and animate undead servants.

A mummy lord's heart embodies the pact that grants it immortality. Rather than bearing its heart within its corpse, a mummy lord removes and hides this accursed organ. As long as its heart isn't destroyed by fire, a mummy lord can return to unlife no matter what doom it meets.

Mummy lords are usually consumed by ageless plots. Roll on or choose a result from the Mummy Lord Plots table to determine a mummy lord's ancient agenda.

**Mummy Lord Plots**

`dice: [](mummy-lord-xmm.md#^mummy-lord-plots)`

| dice: 1d8 | The Mummy Lord Seeks To... |
|-----------|----------------------------|
| 1 | Open a portal to the past, when its power was at its height. |
| 2 | Perform a ritual that can be attempted only once every eight hundred years. |
| 3 | Reclaim and resurrect a loved one's corpse. |
| 4 | Reconquer the lands that once composed its empire. |
| 5 | Recover the pieces of its lost heart. |
| 6 | Replace its descendant as the ruler of a realm. |
| 7 | Sacrifice a thousand souls to its god in return for true life. |
| 8 | Transform the people of an entire nation into Undead servants. |
^mummy-lord-plots

## Mummy Lord Lairs

Mummy lords typically lurk in the ruins of places they dwelled in life. Such sites have forbidding reputations, or they might be lost and forgotten.

> [!quote] A quote from Isu, High Priest of Muhar  
> 
> The scroll contained a foul ritual to raise one of the children of Anhktepot. I tried to burn it, but the flames refused to touch the parchment. Forgive me, but I cannot destroy it... and I cannot help myself.

## Mummies

*Deathless Ancients with Ageless Ambitions*

- **Habitat.** Desert, Swamp  
- **Treasure.** Relics  

Mysterious rites and mighty faith can tie spirits to their corpses, binding them to their remains for all time. Should their resting places be violated, these beings, known as mummies, reanimate their deteriorating bodies to restore the sanctity of their tombs and punish those who disturbed their rest.

Mummies pursue those who offend them, typically mortals who desecrate their resting places, steal their burial treasures, or defile sites tied to their faith. With undying rage, these ancient corpses go to extreme lengths to avenge themselves and restore what they need to find peace.

A mummy might look frail, but its body possesses supernatural strength, and its gaze can strike fear in the bravest hearts. Those who escape a mummy's grasp might find themselves subject to a terrible curse. Victims of a mummy's curse gradually wither, their bodies rotting away until they're reduced to dust. This curse can be healed only by the [Remove Curse](compendium/spells/remove-curse-xphb.md) spell or similar magic.

## Statblock

```ad-statblock
title: Mummy Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Mummy%20Lord.webp#token)
*Small or Medium undead, Lawful Evil*

- **Armor Class** 17
- **Hit Points** 187 (`25d8 + 75`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|17 (+3)|11 (+0)|19 (+4)|16 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +5, Wisdom +9
- **Skills** History +5, Perception +9, Religion +5
- **Senses** truesight 60 ft., passive Perception 19
- **Damage Vulnerabilities** fire
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [exhaustion](rules/conditions.md#Exhaustion), [frightened](rules/conditions.md#Frightened), [paralyzed](rules/conditions.md#Paralyzed), [poisoned](rules/conditions.md#Poisoned)
- **Languages** Common plus three other languages
- **Challenge** 15

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the mummy fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The mummy has [Advantage](rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Undead Restoration.*** If destroyed, the mummy gains a new body in 24 hours if its heart is intact, reviving with all its [Hit Points](rules/variant-rules/hit-points-xphb.md). The new body appears in an unoccupied space within the mummy's lair. The heart is a Tiny object that has AC 17, HP 10, and [Immunity](rules/variant-rules/immunity-xphb.md) to all damage except Fire.

***Spellcasting.*** The mummy casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 17, `+9` to hit with spell attacks):

**At will**: [Dispel Magic](compendium/spells/dispel-magic-xphb.md), [Thaumaturgy](compendium/spells/thaumaturgy-xphb.md)

**1/day each**: [Animate Dead](compendium/spells/animate-dead-xphb.md), [Harm](compendium/spells/harm-xphb.md), [Insect Plague](compendium/spells/insect-plague-xphb.md) (level 7 version)

***Dread Command.*** The mummy casts [Command](compendium/spells/command-xphb.md) (level 2 version), using the same spellcasting ability as Spellcasting. The mummy can't take this action again until the start of its next turn.


## Actions

***Multiattack.*** The mummy makes one Rotting Fist or Channel Negative Energy attack, and it uses Dreadful Glare.

***Rotting Fist.*** *Melee Attack Roll:* `+9`, reach 5 ft. *Hit:* 15 (`2d10 + 4`) Bludgeoning damage plus 10 (`3d6`) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain [Hit Points](rules/variant-rules/hit-points-xphb.md), it gains no benefit from finishing a [Long Rest](rules/variant-rules/long-rest-xphb.md), and its [Hit Point](rules/variant-rules/hit-points-xphb.md) maximum decreases by 10 (`3d6`) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 [Hit Points](rules/variant-rules/hit-points-xphb.md) by this attack.

***Channel Negative Energy.*** *Ranged Attack Roll:* `+9`, range 60 ft. *Hit:* 25 (`6d6 + 4`) Necrotic damage.

***Dreadful Glare.*** *Wisdom Saving Throw:* DC 17, one creature the mummy can see within 60 feet. *Failure:* 25 (`6d6 + 4`) Psychic damage, and the target has the [Paralyzed](rules/conditions.md#Paralyzed) condition until the end of the mummy's next turn.

## Reactions

***Whirlwind of Sand.*** Trigger: The mummy is hit by an attack roll. _Response:_ The mummy adds 2 to its AC against the attack, possibly causing the attack to miss, and the mummy teleports up to 60 feet to an unoccupied space it can see. Each creature of its choice that it can see within 5 feet of its destination space has the [Blinded](rules/conditions.md#Blinded) condition until the end of the mummy's next turn.

## Legendary Actions

***Glare.*** The mummy uses Dreadful Glare. The mummy can't take this action again until the start of its next turn.

***Necrotic Strike.*** The mummy makes one Rotting Fist or Channel Negative Energy attack.
```
^statblock

## Environment

desert, swamp