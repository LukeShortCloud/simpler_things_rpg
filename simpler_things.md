# Simpler Things RPG

## Characters

### Creation

- Pick a Species.
- Pick one Skill to Boost.
- Buy Items with a budget of $1000. Players get to keep the unspent money.

### Traits

Traits effect how good a character is at related Skills.

- Awareness = Social skills and mental strength.
- Knowledge = Philosophy.
- Vitality = Health and power.

Advantages each Trait provides:

- Awareness = Increases the chance of having a higher initiative (to attack first).
- Knowledge = Every point provides a Skill Check that can be rerolled (per game session).
- Vitality = Increases a characters overall health.

### Species

Based on the Species, a player will start with different ranks for their Traits. The maximum number a character can have in any one Trait is 5.

| Name | Awareness | Knowledge | Vitality |
| ---- | --------- | --------- | -------- |
| Alien | 2 | 1 | 1 |
| Human | 1 | 1 | 2 |
| Robot | 1 | 2 | 1 |

## Skills

Each Trait has four related Skills. The Trait stat of a character determines the base number of `d6` dice to roll for a Skill Check. The minimum any character can roll is `1d6`.

| Name | Trait |
| ---- | ----- |
| Convincing | Awareness |
| Electronics | Knowledge |
| Examination | Awareness |
| Fistfight | Vitality |
| Geography | Knowledge |
| Healing | Knowledge |
| Lore | Knowledge |
| Sneak | Awareness |
| Strength | Vitality |
| Stunts | Vitality |
| Weapons (near) | Vitality |
| Weapons (far) | Awareness |

### Boosts

Player Characters start the game with one Skill that is Boosted. Characters can only Boost a Skill once. A Boost adds an extra `1d6` to the related Skill Check.

### Leveling Up

- The Game Master determines when the Player Characters (PCs) level up. Examples of when may be a good time to have players level up:
    - A big quest is completed.
    - Lots of little quests are completed.
    - Every game session.
- Every level up, a PC gets a new Boosted Skill of their choice.
- Every four levels (4, 8, and 12), a PC adds one point to a Trait of their choice: Awareness, Knowledge, or Vitality.
- The maximum level a player can reach is 12. At that level, all Skills have been boosted and one Trait could optionally be maxed out at 5.

## Health

Health = (Vitality x 10) + Armor

Possible Health:

- Minimum = (1 x 10) + 0 = 10
- Medium = (3 x 10) + 15 = 45
- Maximum = (5 x 10) + 25 = 75

When a player character's health is at...

- 0 = They can no longer make an action.
- -10 = Their armor breaks and cannot be repaired/reused.
- -20 = They will get a permanent disability (determined by the GM) and loose at least one Trait point from their highest Trait stat.
- -30 = They die.

## Dice

These are the different types of dice used for Simpler Things.

| Name | Dice Sides | 1 | 2 | 3 | 4 | 5 | 6 |
| ---- | ---------- | - | - | - | - | - | - |
| Omen | 2 | Good | Bad |
| Skill Check (Action) | 6 | 1 | 2 | 3 | 4 | 5 | 6 |
| Skill Check (Side Effect) | 6 | Negative | Neutral | Neutral | Neutral | Neutral | Positive |
| Weapons damage (d2) | 2 | 1 | 2 |
| Weapons damage (d4) | 4 | 1 | 1 | 2 | 2 |

### Skill Checks

When a Player Character (PC) wants to perform an Action, they must tell the party or at least the Game Master (GM). Determine the most related Skill for the Action. The GM determines the Difficulty and it should be a multiple of 3. This is the result that is required for the Action to work.

Rolls:

- Skills Check = `TRAIT x d6`
- Skills Check with a Boost = `(TRAIT x d6) + 1d6`

Difficulty:

- Easiest/minimum = 3
    - This ensures that even if a player has a Skill Check roll of `2d6`, it is possible to fail.
- Hardest/maximum = 36
    - This is the maximum result a PC can get if they have a Trait maxed out at 5 and a Boost in the related Skill. They roll `6d6`.

The GM can determine that a Difficulty needs to be higher than 6. The maximum required result is 12. This requires the PC to have a Boost in the Skill for them to be able to possibly pass the Skill Check. The Boost allows them to roll an additional `1d6`.

**Side Effects**

After a Skill Check, the Player Character must also separately roll `1d6` to determine if there is a Side Effect. The Game Master (GM) determines what the Side Effect will be. It should relate to the Action that was attempted.

Side Effects:
- 1 = Negative
- 2-5 = Neutral or Nothing
- 6 = Positive

The GM tells the players what happens in the game regarding the results of the Skill Check and Side Effect.

**Epic Events**

An Epic Event is when something amazing happens. There are two types: Good and Bad.

A Good Epic Event requires that a Player Character (PC) rolls three `6`s as part of a Skill Check. The PC can describe exactly what happens with their Action. The event should be within reason and must be approved by the Game Master (GM). If damage is being dealt, it will be doubled.

A Bad Epic Event is triggered slightly differently. A PC must roll at least one die that has a result of 1. Then the Side Effect die roll must also result in a 1. The GM determines what horrible thing happens to the PC. Using the Knowledge Trait to reroll cannot stop a Bad Epic Event.

### Omens (Optional)

Before the start of every game session, each Player Character (PC) flips a coin (`1d2`). Heads (1) provides a Good Omen for the player and tails (2) provides a Bad Omen for the GM to use against the player. Each Omen can only be used once for that game session.

A Good Omen allows a Player Character to add an extra `1d6` to any Skill Check for that PC. A Bad Omen allows the GM to increase the Difficulty of a Skill Check for the specified PC by `1d6`.

### Turn Order

All players (PCs and NPCs) must roll a `1d12` (or `2d6`) for their initiative and then add their Awareness to the result. The player with the highest result goes first and then the Turn Order continues in descending order.

Summary:

- Turn Order = `1d12 + (AWARENESS x 1d6)`
- Go in descending order of everyone's results.

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

Each Weapon has a predefined Difficulty. That number also determines the amount of `d2` dice to roll for damage and the cost of it.

- Damage = `DIFFICULTY x d2`
    - It may be more convenient to roll `d4` dice instead of flipping `d2` coins. Roll the `d4` dice, total the number up, round to the next even number if it is odd, and then divide by two.
- Cost = `DIFFICULTY x 100`

#### Weapons (near)

| Name | Difficulty |
| ---- | ---------- |
| Knife | 2 |
| Staff | 3 |
| Hammer | 4 |
| Axe | 5 |
| Sword | 6 |
| Sword, Plasma | 12 |

#### Weapons (far)

| Name | Difficulty |
| ---- | ---------- |
| Slingshot | 2 |
| Spear | 3 |
| Bow | 4 |
| Crossbow | 5 |
| Pistol | 6 |
| Assault Rifle | 8 |
| \*Grenades (3 pack) | 10 |
| Shotgun | 10 |
| Sniper Rifle | 12 |
| \*Grenade, Super (1 pack) | 12 |
| Rocket Launcher | 16 |

\*Grenades have a one-time use and do damage in an area of 10 meters.

**Vehicle**

Vehicle damage is multiplied by 10.

| Name | Difficulty |
| ---- | ---------- |
| Turret (small) | 4 |
| Turret (large) | 8 |

### Healing

Healing requires the use of a Medical Kit. It works similar to Weapons in that a successful Skill Check will result in `DIFFICULTY x d4` of health to be restored. Healing includes repairing armor which should be treated as additional health. Armor only gets destroyed if a player reaches -10 health.

## Magic

Magic works by using the Awareness Trait for a Skill Check. Using Magic that is labeled as a Bad Omen will add a Bad Omen against the player casting the spell.

| Spell | Difficulty | Bad Omen | Description |
| ---- | ---- | -------- | ----------- |
| Brainwash | 6 | No | Manipulate the brain of another character to make them believe or do something temporarily. |
| Crush | 8 | Yes | Exert pressure all around a character or thing to crush it. Does `8d2` damage. |
| Heal | 8 | No | Heal a character for `8d4` health. |
| Heal, Steal | 8 | Yes | Steal health from another character. Take `8d4` health away from the other character and add it to the caster's health. |
| Move | 6 | No | Move objects around with the mind. |
| Revive | 12 | No | Revive a recently killed character. |
| Thunderstorm | 10 | Yes | Manipulate weather by creating a thunderstorm in the casting character's hands. Does `10d2` damage. |

## Vocabulary

### Generic

| Word | Definition |
| ---- | ---------- |
| `d#` | A die that has `#` number of sides. |
| Dice Pool | The entire set of dice a character will roll for their attempt to do their Action. |
| GM | The Game Master is the person who is hosting and controlling the game. |
| NPC | Non-player characters are controlled by the Game Master. |
| PC | The player character refers to the real life people playing the game. |

### Simpler Things

| Word | Definition |
| ---- | ---------- |
| Action | The attempt of a character to use a Skill. |
| Challenge | The difficulty of trying to perform an Action. |
| Epic Event | When a character does something incredible and is narrated by themselves to the group on what happens. |
| Boost | A Skill can become permanently Boosted once. It provides help doing during a Skills Check for an Action by giving the character an extra `1d6` to roll. |
| Omen | An optional game component. A Good Omen can be used by a PC to try to help themselves. A Bad Omen can be used by the GM/NPCs against the PC players. |
| Pass | Used to determine if a player's Action will work. |
| Side Effect | Provides a potential for a favorable or unfavorable outcome of doing an Action. |
| Skills | The core Actions a character can do in the game. |
| Skill Check | The rolling of dice to see if a character can complete an Action. |
| Species | The type of Species represents the Trait levels a character will start with. |
| Traits | Statistics that, along with their possible Boost, affect the amount of dice in a Player Characters' dice pool. |
| STR | Simpler Things RPG. The official name of this open-source game engine. |

## License

[GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html).
