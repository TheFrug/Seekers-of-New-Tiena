---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - compendium/src/5e/xmm
  - monster/cr/2
  - monster/environment/forest
  - monster/environment/urban
  - monster/size/small-or-medium
  - monster/type/monstrosity
aliases:
  - Wererat
---
# Title: 

%%
> [!summary] About This Template This template uses the [[The Eight Steps of Lazy RPG Prep]] document to lay out steps to preparing a game session. The template also includes Obsidian [comments](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Comments) to generate linked [embeds](https://help.obsidian.md/Linking+notes+and+files/Embed+files#Embed+a+note+in+another+note)from that document as helpful reminders for each step.
> 
> > [!tip] You will only see comments in Editing view and the embeds will only render if your Default Editing Mode is set to `Live Preview` (Settings > Editor > Default editing mode).
%%

# Review the Characters

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Review the Characters]]
%%

- [[Lucian Castemur Duskwood]]: A human wizard of noble blood, Lucian is driven to learn the precise truth behind the blast that ended his life ten years ago, hoping to one day restore his family's prestige.
	- Hopes to find [[Pastor Edith]] in the church ASAP
	- Wants to discover what's up with the [[Holly|pixie that was inside the Bulette]] 

- [[Malachi]]: The sole survivor of his [[Xenobium]] of [[Tellers]], the monk Malachi, is a passive observer most of the time, but he sometimes acts in unexpected ways when his heart directs it, which runs counter to the beliefs that were ingrained in him since childhood. 
	- Wants to learn about [[Bromzheath]] and its history
	- Wants to figure out how the party can leave with the relic they seek (the [[Earthmother’s Scythe]])
- [[Calendula Serenada]]: After being soft-exiled from her [[Seelie Court|Seelie]] [[Feywild]] home, Calendula spent some years among mortals, capturing their attention and swindling them for her amusement. However, now that she's caught wind of her best friend, [[Flint]] being alive after years missing, she is determined to find him, although doing so will lead her back into the Seelie-Unseelie conflict that saw her exiled.
	- Learn anything she can about [[Flint]]
- [[Zod Byldamur]]: Imposing in stature, Zod Byldamur is a mountain built upon years of labor as a construction worker, craftsman, and community pillar. After his resurrection, Zod was crushed by the despair of the fall of his life's work, [[Androticus]], as well as the deaths of his family. However, now that he has discovered his sister, [[Kotiri Byldamur|Kotiri]], after years apart, he has found a new motivation to use his intellect and talents to improve the lives of others.
	- Get ready to beat up whatever is in Edith's office!
	- Brainstorm a plan to get the [[Earthmother’s Scythe]]
	- Get a new cool item!

# Create a Strong Start

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Create a Strong Start]]
%%

After finishing their heroic battle with the Bulette, having defended and cared for the frightened crowd of [[Firbolg|Firbolgs]], the party have finally made their way into the [[Church of Chauntea]]. However, where they expect to find [[Brother Merric]], they instead find disorderly pews and the sound of scratching down the hallway to [[Pastor Edith]]'s office. As they turn the dark corner, they come face-to-face with a [[wererat-xmm|Wererat]] in white and red robes, similar to those of the [[Merchant's Caravan]] outside.

#### Encounter Details

 - **How we got here:**
	 - Merric and Edith stay at church
	 - Clungunford sends boys to church to investigate
	 - Increasingly large crowd of Firbolg clamoring to access the church for prayer/confessions
	 - Rose Farmhands arrive, two of them bugger off to the tavern to wait out the situation after a long day's work
	 - Last two successfully make it to the door, and Merric uses magic to tell them to come to the back door
 - **Lighting:** The moonlight glimmers through the stained-glass mural of Chauntea displayed high in the walls of the [[Church of Chauntea]], casting dim light on the scene. 
 - **Enemies:** Ricky Rat, [[Ratmancer]] on the roof of the Church, surrounded by a [[swarm-of-rats-xmm|Swarm of Rats]] guarded by two [[Cult of Talona|cultists]] of [[Talona]], a [[swarm-of-rats-xmm|Swarm of Rats]] feasting on a large Firbolg farmhand, [[Tonks]].
 - **Turn Behaviors:**
	 - Turn 1: Wererat wants inside the office, Swarm of Rats eating Tonks disperse around the church
	 - Turn 2: 
	 - Turn 3: 
	 - Turn 4: 

```statblock
monster: Wererat
```
```statblock  
name: Cultist of Talona  
size: Medium  
type: humanoid  
subtype: string  
alignment: lawful evil  
ac: 13  
hp: 10
hit_dice: 2d8
speed: 30 ft.  
stats: [12, 15, 12, 11, 13, 10]  
skillsaves:  
- Deception: 2
- Religion: 2
damage_resistances: Poison  
condition_immunities: Poisoned, Diseased
senses: Passive Perception 11
languages: Common, Rattish
cr: 1/4
spells:  
- The Cultist of Talona is a 3rd-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 13, +3 to hit with spell)
- <description>  
- 1st level: inflict wounds, detect magic  
traits:
- [Dark Devotion, The fanatic has advantage on saving throws against being Charmed or frightened]
- [Diseased Blood, When struck with slashing or piercing damage, their virulent blood splatters nearby. If it comes into contact with skin, its owner must make a DC 13 Constitution check or be diseased]  
actions: 
- [Envenomed Scimitar, "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:* 5 (1d8 + 2) slashing damage. On hit, targets must make a DC 12 CON save or be poisoned"] 
- [Poisoned Crossbow, "*Ranged Weapon Attack:* +3 to hit, reach 45 ft., one creature. *Hit:* 6 (1d8 + 2) slashing damage + 3 (1d6) poison damage."] 
```
```statblock
monster: Swarm of Rats
```
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
- [Rat Shield, When attacked, the Ratmancer may command a swarm of rats to defend them, gaining +5 AC.]
```

NPCs: 
 - [[Ricky Rat]]: Caravan guard who has now turned into a [[wererat-xmm|Wererat]] and is desperately trying to break into the office at the command of his new master, a cultist who can psychically control rats and wererats.
	 - Goal: Get into Edith's Office and steal the [[Earthmother’s Scythe]]
	 - Ricky Rat is being controlled by the [[Ratmancer]], a [[Cult of Talona|cultist]] of [[Talona]]
	 - If Ricky gets inside, he inspects the scythe for a moment before escaping through the stained-glass window in her office
	 - If the Ratmancer is killed or is otherwise unable to maintain control of Ricky, he will turn himself in
 - [[Ratmancer]]: Is sitting on a swarm of rats atop the roof of the church commanding all nearby rats to do their bidding. Relishing in death and plague, the Ratmancer grins at the flowers around them as they slowly wilt from their mere presence
	 - Goal: Use [[Ricky Rat]], the caravan guard the Ratmancer attacked the previous night, in order to steal the [[Earthmother’s Scythe]]
	 - The Ratmancer stays hidden atop the roof until discovered, at which point they will fight for as long as they still think they can attain the Earthmother’s Scythe
	 - The Ratmancer hates Chauntea, and will not hesitate to ruin the gardens with their plague abilities to hasten their escape
 - Clungunford's Farmboys: Four Firbolg farmhands went into town to investigate the situation with Edith and Merric. They are loyal to Clungunford first, but two are also devout Chaunteand.
 - Some time after arriving and seeing the crowd, two of them abandoned the mission to chill in the tavern. The other two made it into the Church
 - [[Brother Merric]]: Shaggy-haired halfling [[cleric-xphb|Cleric]] of [[Chauntea]] with ties to the [[Cult of Talona]]. The party instructed him to defend the church and the unconscious [[Pastor Edith]] with his life, and to not let anyone into the church
	 - Keep Edith safe at all costs. 
 - [[Pastor Edith]]: Elder Firbolg [[cleric-xphb|Cleric]] of [[Chauntea]]. Edith was last seen unconscious after being struck by a [[Memory Bolt]] and fainting, but was healed by Malachi and left with Brother Merric.

# Outline Potential Scenes

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Outline Potential Scenes]]
%%
 - Ricky Rat's Break-in and Ratmancer's attempted escape 
 - Brother Merric's arrest:
	 - Upon arrival to the scene, [[Baron Clungunford Rose]] demands that Brother Merric be detained in the holding house on suspicion of enabling an attack on the [[Church of Chauntea]]
	 - Evidence: Blocking entry into the church, 
 - Calendula's Nightmare manipulated by [[Dionaea]]
 - 

## To Do

- 



# Define Secrets and Clues

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Define Secrets and Clues]]
%%

 - [[Baron Clungunford Rose|Clungunford Rose]] has the real [[Earthmother’s Scythe]]

# Develop Fantastic Locations

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Develop Fantastic Locations]]
%%

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Outline Important NPCs

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Outline Important NPCs]]
%%

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Choose Relevant Monsters

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Choose Relevant Monsters]]
%%



Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Select Magic Item Rewards

%%
Tip
![[The Eight Steps of Lazy RPG Prep#Select Magic Item Rewards]]
%%


- **Zod:** 
	- Magic Salamander that does something useful and eats wood!
	- 
- **Calendula:** 
	- [[bag-of-tricks-rust-xdmg|Bag of Tricks (Rust)]]
	- 
- **Malachi:** 
	- [[Potion of Pugilism]]: drink for 10 minutes of 1d6 to
	- 
