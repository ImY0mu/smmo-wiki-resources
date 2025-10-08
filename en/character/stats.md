# Stats

## Introduction

In SimpleMMO, each character is described by three main stats: strength (str), defence (def), and dexterity (dex). They can be viewed from the stats page on your profile and the your character page. Stat points are allocated from the `your character` page.

- Strength: Used for damage during world boss fights, NPC fights, and PvP fights. A higher strength means higher damage.
- Defence: Used to lower the amount of damage that you receive from your opponent. A higher defence also lowers the chance that your opponent will successfully hit you.
- Dexterity: Used to increase your chances of successfully hitting your opponent. Dexterity is also a requirement for [quests][1] and spying.

During combat, the two characters’ stats are compared in a series of calculations. The game then rolls for damage dealt based on the outcome of these calculations. Stats can be increased by levelling up, purchasing equipment, and having a profession with a stat bonus.

### Levelling Up

Player will receive 2 stat points for every level up. These can be applied to your character's stats at the Character page.

### Equipment

You can use [equipment][2] to increase your stats by a large amount. Equipment comes in diffrent [rarities][3] and they all provide different stats.

## Resetting Stats
The player is able to reset the stats allocated by pointed gained from their levelling up. When this has been done, their player stats (excluding equipment and professions stat increase) is reset back to zero, and they are available to reallocate all of their stat points. This can be done through two ways:
- Purchasing `Reset Skills` in the diamond store. This costs 15 diamonds at base value or less when there are discounts.
- Using a `Tome of Resetting Skills`, dropped as a normal weapon or purchased through the player market.

## Crit/Special Attack (spATK)
Special attack/crit is a stat that can only be increased through equipmnt. Crit only affects special attacks, which can be used in PvP and PvE battles when you are the attacking player.

Using a special attack consumes one energy point, and boosts the player's strength stat for one turn. The boost is +25% by default. The crit bonus is applied to the str stat before any of the below calculations are performed.

# Combat Mechanics

### Definitions

- Player A has total stats (str <sub>a</sub>, def <sub>a</sub>, dex <sub>a</sub>)
- Player B has total stats (str <sub>b</sub>, def <sub>b</sub>, dex <sub>b</sub>)

These values are the sum of the characters base stats (as shown in their profile) and all of the bonuses from their equipment, jobs, and other buffs.

- Max <sub>ab</sub> () is the maximum damage player A can deal to player B
- Min <sub>ab</sub> () is the minimum damage player A can deal to player B
- CtH <sub>ab</sub> () is the chance player A has to hit player B

### Functions

- Max <sub>ab</sub> (str <sub>a</sub>, def <sub>b</sub>) = str\_a - (9/11)\*def <sub>b</sub>
	- In practice, this function is rounded to the nearest whole number and floored at 20
- Min <sub>ab</sub> (str <sub>a</sub>, def <sub>b</sub>) = str\_a - (11/9)\*def <sub>b</sub>
	- In practice, this function is rounded to the nearest whole number and floored at 1



[1]:/activities-and-challenges/quests
[2]:/items/item-types
[3]:/items/rarities

