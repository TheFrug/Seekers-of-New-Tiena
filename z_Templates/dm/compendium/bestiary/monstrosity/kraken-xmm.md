---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/23
- monster/environment/underwater
- monster/size/gargantuan
- monster/type/monstrosity/titan
aliases: ["Kraken"]
---
# Kraken
*Source: SRD 5.2*  

## Kraken

*Leviathan of Legend*

- **Habitat.** Underwater  
- **Treasure.** Any  

Ancient weapons of the gods, krakens slumber in the deepest oceanic abysses, awaiting their time to rise and dominate the world. These massive, many-tentacled horrors combine overwhelming physical might with formidable cunning. Their powerful limbs shatter ships and topple spires, and they use their control over storms to rain down lightning on their foes.

Krakens usually have little interest in mortal affairs. These terrors were created by the gods to wage war in ages long forgotten. Since that era, most krakens have vanished beneath the waves to slumber until the gods call on them again. Some krakens serve divine masters still, protecting deep sea treasures or entire oceans. Others have forsaken their divine creators and pursue their own agendas, manipulating forces beneath the sea and beyond.

Krakens rarely appear on the surface, but when they do, they herald times of change and doom. When roused to action, these titans directly attack coastal cities or whole armadas. Kraken onslaughts persist until their wrath is sated, their divine patrons are appeased, or their egos are placated by valuable offerings. Roll on or choose a result from the Kraken Attacks table to inspire what ruin a kraken might unleash.

**Kraken Attacks**

`dice: [](kraken-xmm.md#^kraken-attacks)`

| dice: 1d8 | The Enraged Kraken... |
|-----------|-----------------------|
| 1 | Abducts the vessel of a leader or another important community member. |
| 2 | Attacks a community from below using flooded ruins, hidden aquifers, or sewers. |
| 3 | Breaks a lighthouse or seaside tower, carrying it and the occupants to a secret island. |
| 4 | Calls down lightning on any ship that enters its aquatic territory. |
| 5 | Carries ships to an inescapable sargassum. |
| 6 | Dams a river or cuts off a city's sea access. |
| 7 | Devours all sea life near a fishing community, threatening it with ruin. |
| 8 | Masterminds an invasion from the sea by merfolk, sahuagin, or storm giants. |
^kraken-attacks

### Kraken Lairs

Kraken lairs tend to be sunken temples, eldritch ritual sites, or primeval places of divine power. They might lie deep beneath bodies of fresh or salt water, and they often connect to labyrinths of flooded subterranean tunnels or networks of magical portals.

> [!quote] A quote from Malfeore Serrang  
> 
> A kraken dreams of casting its tentacles into the heavens and strangling that which birthed it, and when its dream exceeds its reach, it settles for the occasional passing ship.


```ad-statblock
title: Kraken
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Kraken.webp#token)
*Gargantuan monstrosity (titan), Chaotic Evil*

- **Armor Class** 18
- **Hit Points** 481 (`26d20 + 208`)
- **Speed** 30 ft., swim 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|11 (+0)|26 (+8)|22 (+6)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +17, Dexterity +7, Constitution +15, Wisdom +11
- **Skills** History +13, Perception +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Immunities** cold, lightning
- **Condition Immunities** [frightened](rules/conditions.md#Frightened), [grappled](rules/conditions.md#Grappled), [paralyzed](rules/conditions.md#Paralyzed), [restrained](rules/conditions.md#Restrained)
- **Languages** understands Abyssal, Celestial, Infernal, and Primordial but can't speak; telepathy 120 ft.
- **Challenge** 23

## Traits

***Amphibious.*** The kraken can breathe air and water.

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the kraken fails a saving throw, it can choose to succeed instead.

***Siege Monster.*** The kraken deals double damage to objects and structures.

## Actions

***Multiattack.*** The kraken makes two Tentacle attacks and uses Fling, Lightning Strike, or Swallow.

***Tentacle.*** *Melee Attack Roll:* `+17`, reach 30 ft. *Hit:* 24 (`4d6 + 10`) Bludgeoning damage. The target has the [Grappled](rules/conditions.md#Grappled) condition (escape DC 20) from one of ten tentacles, and it has the [Restrained](rules/conditions.md#Restrained) condition until the grapple ends.

***Fling.*** The kraken throws a Large or smaller creature [Grappled](rules/conditions.md#Grappled) by it to a space it can see within 60 feet of itself that isn't in the air. *Dexterity Saving Throw:* DC 25, the creature thrown and each creature in the destination space. *Failure:* 18 (`4d8`) Bludgeoning damage, and the target has the [Prone](rules/conditions.md#Prone) condition. *Success:* Half damage only.

***Lightning Strike.*** *Dexterity Saving Throw:* DC 23, one creature the kraken can see within 120 feet. *Failure:* 33 (`6d10`) Lightning damage. *Success:* Half damage.

***Swallow.*** *Dexterity Saving Throw:* DC 25, one creature [Grappled](rules/conditions.md#Grappled) by the kraken (it can have up to four creatures swallowed at a time). *Failure:* 23 (`3d8 + 10`) Piercing damage. If the target is Large or smaller, it is swallowed and no longer [Grappled](rules/conditions.md#Grappled). A swallowed creature has the [Restrained](rules/conditions.md#Restrained) condition, has [Total Cover](rules/variant-rules/cover-xphb.md) against attacks and other effects outside the kraken, and takes 24 (`7d6`) Acid damage at the start of each of its turns.

If the kraken takes 50 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 25 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the kraken with the [Prone](rules/conditions.md#Prone) condition. If the kraken dies, any swallowed creature no longer has the [Restrained](rules/conditions.md#Restrained) condition and can escape from the corpse using 15 feet of movement, exiting [Prone](rules/conditions.md#Prone).

## Legendary Actions

***Storm Bolt.*** The kraken uses Lightning Strike.

***Toxic Ink.*** *Constitution Saving Throw:* DC 23, each creature in a 15-foot <span title="Player's Handbook (2024)">Emanation</span> originating from the kraken while it is underwater. *Failure:* The target has the [Blinded](rules/conditions.md#Blinded) and [Poisoned](rules/conditions.md#Poisoned) conditions until the end of the kraken's next turn. The kraken then moves up to its [Speed](rules/variant-rules/speed-xphb.md). *Failure or Success:* The kraken can't take this action again until the start of its next turn.
```
^statblock

## Environment

underwater