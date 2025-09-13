# Dungeon: Temple of Talona

## Backstory
The Temple of Talona is the final bastion of worship for the Mother of Plagues: [[Talona]]. For millennia, [[Cult of Talona|the Talontar]] lived in secret devotion, with its members spread out in a network of temples and traveling clergy all committed to promoting Talona and studying disease and poisons. However, as Talona was slain early into the [[War of the Gods]], she stopped answering her people’s calls, depowering their clerics and essentially dissolving their faith, as the world went centuries without the Plaguemother’s wrath.

As such, the Temple of Talona near [[Bromzheath]], which had historically been one of the most important worship sites of Talona, plunged into cultship, as its members feverishly tried to create a perfect plague and unleash it upon Bromzheath, believing that Talona’s abandonment of them was a punishment for their lack of service ([[Brother Merric]] fled the cult around this time). This all came to a head when the [[Ratmancer]] kidnapped the firbolg [[Pastor Edith]] for use in a ritual to bring about a plague with the potential to revive Talona herself.

## Start & Goal
- Hook: Brother Merric has led the party to the hidden Temple of Talona. The party can talk about their pre-dungeon prep in flashbacks.
	- Clungunford handed the party a envelope with a boar seal. He instructed the party to hand it to the cultists if diplomacy seemed possible, and that it might sway them without bloodshed.
- Goal / what ends the crawl: Find Pastor Edith and bring her back to Bromzheath while ensuring her safety.

## Map & Layout
- Map chosen / rough sketch:
- Loops & landmarks:

## Chambers
- Tags for each chamber (copy this ↓):

### Chamber 1: Narthex
- Tag (1–2 words):
- Notable feature:
- Encounter / challenge:
- Treasure / clue:

## Inhabitants
- Who lives here: Humanoid cultists of Talona, monsters attracted to corpses, long-abandoned servants of Talona 
- What they want: 
	- Cultists: With Pastor Edith in their possession, the leaders of the cult (which includes the Ratmancer) want to sacrifice her as part of a ritual to summon the [[Herald of Rot]]
	- Monsters: Varies
- How they react to intruders:
	- Cultists: So close to their lifelong goal, the cultists will stop at nothing to slow the advance of the party.
	- Monsters: varies
### Monster List
- Quasit: 
```statblock
monster: Quasit
```

- Wererat: 
```statblock
monster: Wererat
```
- The [[Ratmancer]]
```statblock  
name: The Ratmancer
size: Medium  
type: humanoid  
subtype: string  
alignment: lawful evil  
ac: 13 (18 with rat shield) 
hp: 45
hit_dice: 7d8+7
speed: 30 ft.
stats: [9, 15, 12, 12, 17, 16]  
skillsaves:  
- Arcana: 4
- Insight: 6
- Nature: 4
- Religion: 4
damage_resistances: Poison  
condition_immunities: Poisoned, Diseased
senses: Darkvision 60ft., Passive Perception 13
languages: Common, Rattish
cr: 4
spells:  
- The Ratmancer is a 8th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 14, +6 to hit with spell)
- <description>  
- Cantrips: Decompose, Sacred Flame, Shillelagh
- 1st level: inflict wounds, detect magic, ray of sickness, shield
- 2nd level: spike growth, ray of enfeeblement
- 3rd level: stinking cloud
traits:
- [Dark Devotion, The fanatic has advantage on saving throws against being Charmed or frightened]
- [Diseased Blood, When struck with slashing or piercing damage, their virulent blood splatters nearby. If it comes into contact with skin, its owner must make a DC 13 Constitution check or be diseased]  
actions: 
- [Quarterstaff, "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 5 (1d8 + 2, 2d8 + 4 with Shillelagh) bludgeoning damage. On hit, targets must make a DC 12 CON save or be poisoned"] 
- [Poisoned Crossbow, "*Ranged Weapon Attack:* +3 to hit, reach 45 ft., one creature. *Hit:* 6 (1d8 + 2) slashing damage + 3 (1d6) poison damage."] 
reactions:
- [Rat Shield, When attacked the Ratmancer may command a swarm of rats to defend them, gaining +5 AC.]
```
- Gulguthra
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

## Secrets
- Short list of lore / discoveries (~10 max):
- This temple's history shows that other than the regular cultists, there were once frequent visitors from those making offerings of appeasement to [[Talona]]. These appeasement visitations ceased sometime after Talona's death, which led to plagues declining across [[Tiena]]. After that, only the already unscrupulous [[Cult of Talona]] remained to worship her.
	- (Religion 15) All altars come in pairs, one to belay plague, and one to evoke plague. The evoking altars are clean and show signs of use, but the belaying altars are all in states of extreme decay. 
- The [[Cult of Talona]] has been working for [[Baron Clungunford Rose]] for years. However, having caught onto Clungunford's plan to arm the [[Bromzheath Militia]] via trade deal with [[Brenwin's Caravan]], they have decided now is the time to set their plan into motion
	- The note [[Baron Clungunford Rose|Clungunford]] gave the party to give to the Cultists reads: ""
- 

### Party-Specific
- [[Zod Byldamur|Zod]]: 
- [[Lucian Castemur Duskwood|Lucian]]: 
- [[Malachi]]:
- [[Calendula Serenada|Calendula]]:

## Boss / Climax
- Set piece: 
- Terrain twist: 
- Other ways to “win”: 

## Rewards
- Loot:
- Cool consumable:
- Memorable item:

## Atmosphere
- Sight:
- Sound:
- Smell / vibe:

## Exit
- Signal that it’s over:
- Shortcut out:

## Flex Tools
- Random encounter table:
- Reskin rooms:
- Spare names:
