# Simpler Things RPG Engine

An open source role-playing table-top game engine.

Goals:

* Simple rules
* Quick references
* Fast setup time for new campaigns and players
* Flexible enough to work with any genre

## Characters

### Traits

* Awareness = Social skills and mental strength.
* Knowledge = Smart and wise.
* Vitality = Health and power.

### Species

Based on the species, a player will start with different ranks for their traits.

| Name | Awareness | Knowledge | Vitality |
| ---- | ------ | --------- | -------- |
| Alien | 4 | 2 | 2 |
| Human | 2 | 2 | 4 |
| Robot | 2 | 4 | 2 |

## Expertise

| Name | Trait |
| ---- | ----- |
| Convincing | Awareness |
| Driving | Knowledge |
| Electronics | Knowledge |
| Examination | Awareness |
| Geography | Knowledge |
| Gun | Vitality |
| Healing | Vitality |
| Lore | Knowledge |
| Sneak | Awareness |
| Stunts | Vitality |
| Sword | Vitality |

### Jobs

Jobs provide characters with a set of three Expertise to start off with.

* Electrician = Electronics, Examination, Gun
* Monk = Examination, Healing, Lore
* Officer = Gun, Lore, Stunts
* Pilot = Driving, Electronics, Geography
* Secret Agent = Examination, Convincing, Sneak
* Swordsman = Geography, Stunts, Sword
* Teacher = Convincing, Geography, Lore

Note: When adding new jobs to this list, no two jobs should have two or more overlapping Expertise.

### Creation

* Pick a species.
* Pick a job.

### Leveling Up

* Every level up, a player can add one point to any Trait.
* Every four level ups (5, 9, 13, etc.), a player gets a new Expertise of their choice.

## Health

Health = Vitality x 5

## Dice

The only dice required are standard six-sided dice (d6).

| Name | 1 | 2 | 3 | 4 | 5 | 6 |
| ---- | - | - | - | - | - | - |
| Action | | | | Pass | Pass | Pass |
| Expertise | | | | Improvement | Improvement | Improvement |

### Actions, Improvements, and Epic Events

There are two pools of dice that are rolled. The first by the PC and then the second by the GM representing the environment or NPC. The results of both cancel each other other.

The GM may use any number of Action or Expertise dice, based on the scenario. The dice pool for the PC, however, is precisely calculated. For every two points of a Trait, a character can roll one Action dice. For every four points of a Trait, a character can also add an Expertise dice.

If a character gets an Improvement then something favorable happens to them, even if the exact Action they were doing does not Pass. Getting a negative Improvement will result in something undesirable happening as a result of the Action. The GM decides what the favorable or undesirable outcome is.

Getting five Improvements will result in an Epic Event. The PC can describe exactly what happens during with their Action (within reason and with approval of the GM). If damage is being dealt, it will be doubled.

### Omens

During the first session of the game, each PC should flip a coin or roll a d6 to determine if they get a Bad (1-3) or Good (4-6) Omen. With a Good Omen, a PC can add an extra Expertise die to their dice pool. With a Bad Omen, the GM can add an extra Expertise die to an NPC that is using an Action against the PCs. Once an Omen is used, it is converted to the opposite site. This means when a Good Omen is used, it becomes a Bad Omen. An Omen for/against a PC can only be used once per session. The PCs should record what Omen type they have at the end of each session.

### Turn Order

All players (PCs and NPCs) must roll a d12 (or two d6) for their initiative. They can add one to their Turn Order roll for every four points in Awareness. The player with the highest result goes first and then the Turn Order continues in descending order.

### Examples

Passes:
*  If there was one Pass for the PC and two Passes for the GM means that the player fails at their Action (they got -1 Pass).

Expertise:
* A roll for a character with the Geography (Expertise) who has a Knowledge (Trait) of six will get to roll three Action dice (6 / 2 = 3) and one Expertise die (6 / 4 = 1.5).

Epic Event:
* A player happens to have gotten a maximum of six Improvements from rolling two Expertise dice for their Electronics check. This results in an Epic Event (6 >= 5). The player describes how they managed to access the system using their own decryption method and gained additional information about their arch nemesis that the group was not originally planning on finding.

Omens:
* A player tries to make an ambitious jump from one cliff to another. That player has a Bad Omen so the GM decides to make it harder for them and uses it to add an extra Expertise die against them. After this, the player gets a Good Omen they can use during the next game session.

Turn Order:
* PC 1 has ten points in Awareness and rolls a total of nine. Their Turn Order would be 9 (7 + (10 / 4)) . PC two has 2 points in Awareness and rolls a maximum of 12. Their Turn Order would be 12 (12 + (2 / 4)). PC 2 goes first. PC 1 goes after them.

## Vocabulary

### Generic

| Word | Definition |
| ---- | ---------- |
| d6 | A 6-sided die. |
| d12 | A 12-sided die. |
| Dice Pool | The entire set of dice a character will roll for their attempt to do their Action. |
| GM | The Game Master is the person who is hosting and controlling the game. |
| NPC | Non-player characters are controlled by the Game Master. |
| PC | The player character refers to the real life people playing the game. |

### Simpler Things

| Word | Definition |
| ---- | ---------- |
| Action | When a character tries to use their Skills or Expertise. |
| Epic Event | When a character does something incredible and is narrated by themselves to the group on what happens. |
| Expertise | Provides a potential for a favorable alternative outcome. |
| Improvement | Used to determine if a player's Action will have positive, negative, or no side affects. |
| Jobs | A job represents the 3 related skills a character will start with. |
| Omen | A Good Omen can be used by a PC to try to help themselves or a Bad Omen can be used by the GM to try to harm a PC.
| Pass | Used to determine if a player's Action will work. |
| Species | The type of Species represents the Trait levels a character will start with. |
| Traits | Statistics that, along with their Expertise, affect the amount of dice in a Player Characters' dice pool. |

## License

[GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html).
