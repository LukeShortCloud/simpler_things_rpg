# Simpler Things RPG

## Characters

### Traits

Traits effect how good a character is at related Skills.

* Awareness = Social skills and mental strength.
* Knowledge = Philosophy.
* Vitality = Health and power.

### Species

Based on the Species, a player will start with different ranks for their Traits. The maximum number a character can have in any Trait is 10.

| Name | Awareness | Knowledge | Vitality |
| ---- | --------- | --------- | -------- |
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
| Healing | Vitality |
| Magic\* | Awareness |
| Lore | Knowledge |
| Sneak | Awareness |
| Stunts | Vitality |
| Weapons (near) | Vitality |
| Weapons (far) | Vitality |

Notes:

- \*Magic can only be used by player characters that start the game with it as an Expertise.

### Jobs

Jobs provide characters with a set of three different Skills Expertise to start off with. A character can only become an Expert in a Skill once. An Expertise adds an extra `1d6` to the related Skill check.

| Job | Expertise 1 | Expertise 2 | Expertise 3 |
| --- | ----------- | ----------- | ----------- |
| Administrator | Healing | Electronics | Weapons (far) |
| Adventurer | Examination | Geography | Lore |
| Doctor | Convincing | Examination | Healing |
| Electrician | Electronics | Examination | Weapons (near) |
| Hacker | Electronics | Sneak | Stunts |
| Monk | Healing | Lore | Magic |
| Ninja | Sneak | Stunts | Weapons (near) |
| Nomad | Lore | Magic | Weapons (far) |
| Officer | Healing | Stunts | Weapons (far) |
| Pilot | Driving | Electronics | Geography
| Protector | Driving | Magic | Weapons (near) |
| Refugee | Magic | Sneak | Weapons (far) |
| Secret Agent | Convincing | Examination | Sneak
| Swordsman | Geography | Stunts | Weapons (near) |
| Teacher | Convincing | Geography | Lore |

### Creation

* Pick a Species.
* Pick a Job.
* Buy Items with a budget of $1000. Players get to keep the unspent money.

### Leveling Up

* Every level up, a player can add one point to any Trait.
* Every four level ups (5, 9, 13, etc.), a player gets a new Expertise of their choice.

## Health

Health = (Vitality x 10) + Armor

Possible Health:

* Minimum = (2 x 10) + 0 = 20
* Maximum = (10 x 10) + 25 = 125

When a player character's health is at...

* 0 = They can no longer make an action.
* -10 = Their armor breaks and cannot be repaired/reused.
* -20 = They will get a permanent disability (determined by the GM) and loose at least one Trait point.
* -30 = They die.

Healing requires the use of a Medical Kit. It works similar to Weapons. The base difficulty is `2d6` and can be adjusted by the GM. A successful Healing action will restore `PASSES x d4` health. A failed Health action will taken away `PASSES x d4` health. Healing includes repairing armor which should be treated as additional health. Armor only gets destroyed if a player reaches -10 health.

- Passes or Failures = (`HEALING_SKILL x d6`) - `2d6`
- Health restored = `PASSES x d4`
- Health lost = `FAILURES x d4`

## Dice

These are the different types of dice used for Simpler Things.

| Name | Dice Sides | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| ---- | ---------- | - | - | - | - | - | - | - | - | - | -- |
| Omen | 2 | Good | Bad |
| Skill Check (Action) | 6 | 1 | 2 | 3 | 4 | 5 | 6 |
| Skill Check (Side Effect) | 6 | Negative | Negative | Neutral | Neutral | Positive | Positive |
| Weapons damage (character sized) | 4 | 1 | 2 | 3 | 4 |
| Weapons damage (vehicle sized) | 10 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

### Skill Checks

When a Player Character (PC) wants to perform an Action, they must tell the party or at least the Game Master (GM). Determine the most related Skill for the Action. The GM determines the Difficulty. This is the result that is required for the Action to work. The PC then rolls `1d6` (or `2d6` if the Skill is an Expertise).

Difficulty:
- Easiest/minimum = 3
- Hardest/maximum = 12

The GM can determine that a Difficulty needs to be higher than 6. The maximum required result is 12. This requires the PC to have an Expertise in the Skill for them to be able to possibly pass the Skill Check. The Expertise allows them to roll an additional `1d6`.

**Side Effects**

After a Skill Check, the Player Character must also separately roll `1d6` to determine if there is a Side Effect. The Game Master (GM) determines what the Side Effect will be. It should relate to the Action that was attempted.

Side Effects:
- 1-2 = Negative
- 3-4 = Neutral or Nothing
- 5-6 = Positive

The GM tells the players what happens in the game regarding the results of the Skill Check and Side Effect.

**Epic Events**

An Epic Event is when something amazing happens. There are two types: Good and Bad.

A Good Epic Event requires that a Player Character (PC) has an Expertise in a Skill and rolls a total result of 12 for their `2d6` Skills Check. A PC without an Expertise in a Skill can only, at most, get a result of 6 and not 12 because they can only roll `1d6`. The PC can describe exactly what happens with their Action. The event should be within reason and must be approved by the Game Master (GM). If damage is being dealt, it will be doubled.

A Bad Epic Event is triggered slightly differently. A PC must roll at least one die that has a result of 1. Then the Side Effect die roll must also result in a 1. The GM determines what horrible thing happens to the PC.

### Omens (Optional)

Before the start of every game session, each player should flip a coin (`1d2`). Heads (1) provides a Good Omen for the player and tails (2) provides a Bad Omen for the GM to use against the player. Each Omen can only be used once for that game session. An Omen adds `2d6` to any Skill Check.

### Turn Order

All players (PCs and NPCs) must roll a `1d12` (or `2d6`) for their initiative and then add their Awareness to the result. The player with the highest result goes first and then the Turn Order continues in descending order.

Summary:

* Turn Order = `1d12 + AWARENESS`
* Go in descending order of everyone's results.

### Examples

Passes:
*  If there was one Pass for the PC and two Passes for the GM means that the player fails at their Action (they got -1 Pass).

Expertise:
* A roll for a character with the Geography (Expertise) who has a Knowledge (Trait) of six will get to roll seven Action dice. They get the extra dice for having an Expertise in the Skill.

Epic Event:
* A player does a Skill Check for Electronics. They roll `5d6` and get the numbers: 4, 6, 6, 6, and 6. This triggers an Epic Event. The player describes how they managed to access the system using their own decryption method and gained additional information about their arch nemesis that the group was not originally planning on finding there.

Omens:
* A player tries to make an ambitious jump from one cliff to another. That player has a Bad Omen and the GM decides to make it harder for themto succeed. The GM upgrades the difficulty of the `Stunts` Skill check by adding `2d6`.

Turn Order:
* PC 1 has ten points in Awareness and rolls an eleven from a `1d12`. Their Turn Order would be 16 (11 + (10 / 2)) . PC 2 has two points in Awareness and rolls a maximum of 12 from a `1d12`. Their Turn Order would be 18 (12 + (12 / 2)). PC 1 goes first. PC 1 can do an action after PC 2.

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

Each Weapon has a Rank which determines how many Passes are required to successfully hit a target, how much damage it will do, and how much money it will cost to buy. The base difficulty to use any Weapon is `2d6` which is what the GM will roll. The GM can adjust the difficulty based on the situation. Subtract the results of the difficulty from the Skill Check for the related Weapon type (near or far) to get the Pass number. For the Action to work, that number should equal or exceed the Rank. Roll the Rank number of `d4` dice for damage. The cost to buy a weapon is `RANK x 200`.

- Passes = `2d6` - (`RANK x d6`)
- Damage = `RANK x d4`
- Cost = `RANK x 200`

#### Weapons (near)

| Name | Rank | Cost |
| ---- | ---- | ---- |
| Knife | 1 | 200 |
| Staff | 2 | 400 |
| Hammer | 3 | 600 |
| Axe | 4 | 800 |
| Sword | 5 | 1000 |
| Sword, Plasma | 10 | 2000 |

#### Weapons (far)

| Name | Rank | Cost |
| ---- | ---- | ---- |
| Slingshot | 1 | 200 |
| Spear | 2 | 400 |
| Bow | 3 | 600 |
| Pistol | 4 | 800 |
| Crossbow | 5 | 1000 |
| Assault Rifle | 6 | 1200 |
| \*Grenades (3 pack) | 7 | 1400 |
| Shotgun | 8 | 1600 |
| Sniper Rifle | 9 | 1800 |
| \*Grenade, Super (1 pack) | 10 | 2000 |

\*Grenades have a one-time use and do damage in an area of 10 meters.

**Vehicle (d10 Damage)**

| Name | Rank |
| ---- | ---- |
| Turret (small) | 3 |
| Turret (large) | 5 |

## Magic

Magic is difficult to use yet very powerful when it actually works. Only a character with Expertise in Magic can use it. The base difficulty to successfully cast a Spell is `4d6`. Characters have access to all of the available Spells.

Using Magic that is labeled as a Bad Omen will add a Bad Omen against the player casting the spell.

| Spell | Rank | Bad Omen | Description |
| ---- | ---- | -------- | ----------- |
| Brainwash | 6 | | Manipulate the brain of another character to make them believe or do something temporarily. |
| Crush | 6 | Yes | Exert pressure all around a character or thing to crush it. Does `6d4` damage. |
| Heal | 7 | | Heal a character for `7d4` health. |
| Heal, Steal | 8 | Yes | Steal health from another character. Take `8d4` health away from the other character and add it to the caster's health. |
| Kill | 10 | Yes | Instantly kill any character of equal or lesser Vitality. |
| Move | 5 |  | Move objects around with the mind. |
| Revive | 9 | | Revive a recently killed character. |
| Thunderstorm | 7 | Yes | Manipulate weather by creating a thunderstorm in the casting character's hands. Does `7d4` damage. |

## Quick Start

* The Game Master (GM) decides the genre, time, and setting for a game.
* Player Characters (PCs) use a Character Sheet and fill it out by following the Characters Creation guide.
* (Optional) Each PC rolls `1d2` to determine if they start with a Good (1) or Bad (2) Omen.
* PCs can interact with anything in the game based off of their Skills and the related Traits. This is called an Action.
    * `TRAIT x d6`
    * If they have an Expertise in a Skill, they can roll one extra six-sided die.
    * (Optional) An Omen can be used once per game session to add two six-sided die (`2d6`) to the Action pool.
* The GM decides how Challenging an Action is based on the situation.
    * `CHALLENGE x d6`
* The GM determines the output of an Action.
    * Positive or Negative Pass = The PC successfully completes or fails their Action.
    * Positive or Negative Side Effect = A good or bad side effect (related event) happens as a result of the Action. This is determined by the GM.
    * Epic Event (four separate `1d6` dice naturally land on a 6) = The Action is so perfectly executed that something amazing happens. If the PC triggers an Epic Event, they can narrate what happens.
        * If this is for a Weapons related Action, the damage will be doubled.
* Combat
    * Everyone rolls for their Turn Order. The characters with the highest number goes first.
        * `1d12 + AWARENESS`
    * For a Weapons Action to Pass, a character must get the same number of Passes as the number of Rank the Weapon has listed.
        * If the Action Passes, the character rolls `WEAPON RANK x d4` for damage for normal handheld Weapons. For vehicle Weapons, the roll for damage is `WEAPON RANK x d10`.
* Magic
    * Works the same as any normal Skill check except it requires that a character has an Expertise in Magic to use it at all.
    * If it Passes, the PC can narrate what happens as a result of their Action (within reason and with approval from the GM).

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
| Expertise | Provides help doing during a Skills Check for an Action by giving the character an extra `1d6` to roll. |
| Job | A job represents 3 related skills a character will start with. |
| Omen | An optional game component. A Good Omen can be used by a PC to try to help themselves. A Bad Omen can be used by the GM/NPCs against the PC players. |
| Pass | Used to determine if a player's Action will work. |
| Side Effect | Provides a potential for a favorable or unfavorable outcome of doing an Action. |
| Skills | The core Actions a character can do in the game. |
| Skill Check | The rolling of dice to see if a character can complete an Action. |
| Species | The type of Species represents the Trait levels a character will start with. |
| Traits | Statistics that, along with their Expertise, affect the amount of dice in a Player Characters' dice pool. |
| STRE | Simpler Things RPG Engine. The official name of this open-source game engine. |

## License

[GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html).
