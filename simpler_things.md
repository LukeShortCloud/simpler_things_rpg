# Simpler Things RPG Engine

An open source role-playing table-top game engine.

Goals:

* Simple rules
* Quick references
* Fast setup time for new campaigns and players
* Flexible enough to work with any genre

## Characters

### Traits

Traits effect how good a character is at related Skills.

* Awareness = Social skills and mental strength.
* Knowledge = Philosophy.
* Vitality = Health and power.

### Species

Based on the Species, a player will start with different ranks for their Traits. The maximum number a character can have in any Trait is 10.

| Name | Awareness | Knowledge | Vitality |
| ---- | ------ | --------- | -------- |
| Alien | 4 | 2 | 2 |
| Human | 2 | 2 | 4 |
| Robot | 2 | 4 | 2 |

## Skills

Each Trait has four related Skills.

| Name | Trait |
| ---- | ----- |
| Convincing | Awareness |
| Driving | Knowledge |
| Electronics | Knowledge |
| Examination | Awareness |
| Geography | Knowledge |
| Healing\* | Vitality |
| Magic | Awareness |
| Lore | Knowledge |
| Sneak | Awareness |
| Stunts | Vitality |
| Weapons (blades) | Vitality |
| Weapons (ranged) | Vitality |

\*Healing takes two turns to complete, instead of one.

### Jobs

Jobs provide characters with a set of three different Skills Expertise to start off with. A character can only become an Expert in a Skill once. An Expertise adds an extra 1d6 to the related Skill check.

* Electrician = Electronics, Examination, Gun
* Monk = Healing, Lore, Magic
* Officer = Weapons (ranged), Lore, Stunts
* Pilot = Driving, Electronics, Geography
* Secret Agent = Examination, Convincing, Sneak
* Swordsman = Geography, Stunts, Weapons (blades)
* Teacher = Convincing, Geography, Lore

Note: When adding new jobs to this list, no two jobs should have two or more overlapping Expertise.

### Creation

* Pick a Species.
* Pick a Job.
* Buy Items with a budget of $1000. Players get to keep the unspent money.

### Leveling Up

* Every level up, a player can add one point to any Trait.
* Every four level ups (5, 9, 13, etc.), a player gets a new Expertise of their choice.

## Health

Health = Vitality + Armor + 10

Possible Health:

* Minimum = 2 + 0 + 10 = 12
* Maximum = 10 + 25 + 10 = 45

## Dice

These are the different types of dice used in Simpler Things. The dice that will be most commonly used are d6 and d4 for the Action and Weapons damage (character sized).

Recommended dice:

* Five d4, d6, and d10.

| Name | 1 | 2 | 3 | 4 | 5 | 6 |
| ---- | - | - | - | - | - | - |
| Action | | | | Pass | Improvement | Pass and Improvement |
| Omen | Bad | Bad | Bad | Good | Good | Good |

| Name | 1 | 2 | 3 | 4 |
| ---- | - | - | - | - |
| Weapons damage (character sized) | 1 | 2 | 3 | 4 |

| Name | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| ---- | - | - | - | - | - | - | - | - | - | -- |
| Weapons damage (vehicle sized) | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

### Skill Checks

**Actions**

When a player wants to do an Action with a Skill, they must roll for it. There are two pools of dice that are rolled. The first is by the PC based on their Trait and, if available, their Expertise of a Skill. The second is handled by the GM representing the environment or a NPC based on how Challenging they think the Action should be. The results of both cancel each other. One Pass from the GM cancels out one Pass from the PC. The PC needs at least one Pass to complete the Action.

The dice pool for the PC is a group of d6 dice. The related Trait of the Skill will need to be looked up. The PC's level in that Trait determines the number of d6 dice to roll. If they also have an Expertise in the Skill, they get to roll an extra 1d6.

**Improvements**

If a character gets at least one Improvement then something favorable happens to them, even if the Action they were doing does not Pass. Getting a negative Improvement will result in something undesirable happening as a result of the Action. The GM decides what the favorable or undesirable outcome is.

**Challenge**

The GM determines the Challenge of a Skills check based on the situation. The harder an action is estimated to be, the more Action dice the GM rolls against the PCs. If the GM rolls more Passes than the PC, then the PC's Action does not pass. If the GM rolls more Improvements than the PC, then a negative event happens to the PC.

The GM may use any number of Action or Expertise dice, based on what they think the Challenge of a scenario should be.

**Epic Events**

Getting five Improvements OR rolling four dice with a result of 6 on each one will result in an Epic Event. The PC can describe exactly what happens during with their Action (within reason and with approval of the GM). If damage is being dealt, it will be doubled.

Summary:

* Triggers for an Epic Event
    * Five Improvements or...
    * Four "6" results from a d6 Action roll.

### Omens

During the first session of the game, each PC should flip a coin or roll a d6 to determine if they get a Bad (1-3) or Good (4-6) Omen. With a Good Omen, a PC can add two extra Action dice to their dice pool. With a Bad Omen, the GM can add two extra Action die to for a NPC that is using an Action. Alternatively, the GM may also use two extra Action die for a Challenge Check. Once an Omen is used, it is converted to the opposite side. This means that when a Good Omen is used it becomes a Bad Omen. An Omen for/against a PC can only be used once per session. The PCs should record what Omen type they have at the end of each session.

Summary:

* An Omen can be Good (helps the PC) or Bad (helps the GM).
* An Omen for a character can only be used once per game session.
* An Omen adds 2d6 to a Skills Check for an Action.

### Turn Order

All players (PCs and NPCs) must roll a 2d6 (or 1d12) for their initiative. They can add one to their Turn Order roll for every three points in Awareness. The player with the highest result goes first and then the Turn Order continues in descending order.

Summary:

* Turn Order = `1d12 + (Awareness / 3)`
* Go in descending order of everyone's results.

### Examples

Passes:
*  If there was one Pass for the PC and two Passes for the GM means that the player fails at their Action (they got -1 Pass).

Expertise:
* A roll for a character with the Geography (Expertise) who has a Knowledge (Trait) of six will get to roll seven Action dice. They get the extra dice for having an Expertise in the Skill.

Epic Event:
* A player happens to have gotten a maximum of six Improvements from rolling two Expertise dice for their Electronics check. This results in an Epic Event (6 >= 5). The player describes how they managed to access the system using their own decryption method and gained additional information about their arch nemesis that the group was not originally planning on finding.

Omens:
* A player tries to make an ambitious jump from one cliff to another. That player has a Bad Omen so the GM decides to make it harder for them and uses it to add an extra Expertise die against them. After this, the player gets a Good Omen they can use during the next game session.

Turn Order:
* PC 1 has ten points in Awareness and rolls an eleven from a 1d12. Their Turn Order would be 14 (11 + (10 / 3)) . PC 2 has two points in Awareness and rolls a maximum of 12 from a 1d12. Their Turn Order would be 12 (12 + (2 / 3)). PC 1 goes first. PC 2 goes after them.

## Items

### Armor

| Name | Health Boost | Cost |
| ---- | ------------ | ---- |
| Tier 1 | 5 | 500 |
| Tier 2 | 10 | 1000 |
| Tier 3 | 15 | 2000 |
| Tier 4 | 20 | 4000 |
| Tier 5 | 25 | 8000 |

### Weapons

Each Weapon has a Rank based on how easy or hard it is to use. The Rank is the number of Passes required for the Weapon to successfully attack with. It is also the number of dice to roll for the attack damage. Character sized weapons do d4 damage. Vehicle sized weapons do d10 damage. For example, an Assault Rifle that has Rank 2 will require two Passes. For damage, 2d4 dice will be rolled.

Summary:

* Rank = Passes required to successfully attack with that Weapon.
* Rank = If the attack Passes, use the Rank number of d4 or d10 dice to roll for damage.

#### Weapons (blades)

| Name | Rank | Cost |
| ---- | ---- | ---- |
| Knife | 1 | 100 |
| Sword | 3 | 500 |
| Sword, Plasma | 6 | 10000 |

#### Weapons (ranged)

| Name | Rank | Cost |
| ---- | ---- | ---- |
| Assault Rifle | 2 | 600 |
| Grenades (3 pack) | 4 | 1000 |
| Grenade, Super (1 pack) | 5 | 5000 |
| Pistol | 1 | 100 |
| Shotgun | 3 | 1000 |
| Sniper Rifle | 5 | 7500 |

Vehicle (d10 Damage)

| Name | Rank |
| ---- | ---- |
| Turret (small) | 3 |
| Turret (large) | 5 |

## Vocabulary

### Generic

| Word | Definition |
| ---- | ---------- |
| d`#` | A die that has `#` number of sides. |
| Dice Pool | The entire set of dice a character will roll for their attempt to do their Action. |
| GM | The Game Master is the person who is hosting and controlling the game. |
| NPC | Non-player characters are controlled by the Game Master. |
| PC | The player character refers to the real life people playing the game. |

### Simpler Things

| Word | Definition |
| ---- | ---------- |
| Action | The attempt of a character to use a Skill. |
| Epic Event | When a character does something incredible and is narrated by themselves to the group on what happens. |
| Expertise | Provides help doing during a Skills Check for an Action by giving the character an extra 1d6 to roll. |
| Improvement | Provides a potential for a favorable or unfavorable alternative outcome of doing an Action. |
| Job | A job represents 3 related skills a character will start with. |
| Omen | A Good Omen can be used by a PC to try to help themselves. A Bad Omen can be used by the GM to try to harm a PC.
| Pass | Used to determine if a player's Action will work. |
| Skills | The core Actions a character can do in the game. |
| Skills Check | The rolling of dice to see if a character can complete an Action. |
| Species | The type of Species represents the Trait levels a character will start with. |
| Traits | Statistics that, along with their Expertise, affect the amount of dice in a Player Characters' dice pool. |

## License

[GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html).
