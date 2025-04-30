---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/5
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/construct
aliases: ["Gorgon"]
---
# Gorgon
*Source: SRD 5.2*  

Most gorgons are iron bulls wreathed in clouds of petrifying gas. Their metal plates vary in sheen and color, from sleek silver to pitted black. The oldest gorgons might be covered in rust, but this rarely impedes their abilities. These gorgons' stomping grounds are littered with the shattered remains of [petrified](conditions.md#Petrified) foes. Many gorgons outlive their creators by centuries, misleading some to believe these creations have natural origins and territories. Most such gorgons continue to follow age-old commands, guarding sites long fallen to ruin.

## Gorgons

*Bull-like Guardians with Petrifying Breath*

- **Habitat.** Forest, Grassland, Hill  
- **Treasure.** Any  

Resembling mighty bulls armored in iron plates, gorgons are lifelike automatons that seek to destroy all who enter their territories. In addition to goring foes with their deadly horns and trampling them under their iron hooves, gorgons exhale gouts of noxious gas.

Gorgons are created by magic-users to serve as guardians. The process for creating a gorgon is labor intensive and dangerous, with one method requiring the skeleton of a bull, the blood of a medusa, and the brain of a basilisk fused into a frame of ensorcelled iron. If the process fails, petrifying gas emerges from the materials, creating a magical threat that can fill a structure and linger for years.

When magic-users create gorgons, they often enchant them to ignore those who confront the creature with a specific command key, usually a password or a specific signal. Once a gorgon is set to guard an area, it attacks any who enter until they flee or are destroyed. Should someone provide the command key, the monster ignores that intruder so long as the intruder remains in its sight. But if the intruder ventures out of sight and then returns without again presenting the command key, the gorgon attacks. Those in a gorgon's territory must remain vigilant and aware of the monster's exact position, or they risk being attacked by a gorgon they thought was no longer a threat.

Those who create gorgons strive to give them purposefully obscure command keys. Hints at command keys might be found among the records of a gorgon's creator or in the area the gorgon protects—perhaps scrawled as a [petrified](conditions.md#Petrified) trespasser's final act. Roll on or choose a result from the Gorgon Command Keys table to inspire the word or signal that temporarily neutralizes a gorgon.

**Gorgon Command Keys**

`dice: [](gorgon-xmm.md#^gorgon-command-keys)`

| dice: 1d6 | Gorgon Won't Attack Those That... |
|-----------|-----------------------------------|
| 1 | Cast a particular spell in the gorgon's presence. |
| 2 | Keep their back to the gorgon or otherwise act like they don't see the monster. |
| 3 | Offer it a drink of blood, water, or wine. |
| 4 | Recite a specific rhyme or sing a certain song. |
| 5 | Say its creator's name backward. |
| 6 | Wear a mask, perhaps in the shape of a bull or an animal meaningful to the gorgon's creator. |
^gorgon-command-keys

> [!quote] A quote from Lum the Maestro  
> 
> Notable among my eccentric ancestor's scattered designs was a schematic of a swamp-dwelling bovine monster and an ominous note: "Do better."


## Statblock

```ad-statblock
title: Gorgon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Gorgon.webp#token)
*Large construct, Unaligned*

- **Armor Class** 19
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|11 (+0)|18 (+4)| 2 (-4)|12 (+1)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +7
- **Senses** darkvision 60 ft., passive Perception 17
- **Condition Immunities** [exhaustion](rules/conditions.md#Exhaustion), [petrified](rules/conditions.md#Petrified)
- **Languages** —
- **Challenge** 5

## Actions

***Gore.*** *Melee Attack Roll:* `+8`, reach 5 ft. *Hit:* 18 (`2d12 + 5`) Piercing damage. If the target is a Large or smaller creature and the gorgon moved 20+ feet straight toward it immediately before the hit, the target has the [Prone](rules/conditions.md#Prone) condition.

***Petrifying Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 15, each creature in a 30-foot [Cone](rules/variant-rules/cone-area-of-effect-xphb.md). *1st Failure:* The target has the [Restrained](rules/conditions.md#Restrained) condition and repeats the save at the end of its next turn if it is still [Restrained](rules/conditions.md#Restrained), ending the effect on itself on a success. *2nd Failure:* The target has the [Petrified](rules/conditions.md#Petrified) condition instead of the [Restrained](rules/conditions.md#Restrained) condition.

## Bonus Actions

***Trample.*** *Dexterity Saving Throw:* DC 16, one creature within 5 feet that has the [Prone](rules/conditions.md#Prone) condition. *Failure:* 16 (`2d10 + 5`) Bludgeoning damage. *Success:* Half damage.
```
^statblock

## Environment

forest, grassland, hill