# Stats

## Introduction

In SimpleMMO, each character is described by three main stats: strength (str); defence (def); and dexterity (dex). During combat, the two combating characters’ stats are compared in a series of calculations. The game then rolls for damage dealt based on the outcome of these calculations. Additionally, dex alone is used to determine the chance of completing a [quest](https://simplemmo.fandom.com/wiki/Quests). Stats can be boosted by leveling up, purchasing equipment, and having a profession with a stat bonus.

### Levelling Up

Player will recieve 2 stat points for every level up. These can be applied to your character's stats at the Character page.

### Equipment

You can use [equipment][1] to boost your stats by a large amount. Equipment comes in diffrent [rarities][2] and they all provide diffrent stats.

## Combat Mechanics

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




[1]:/items/item-types
[2]:/items/rarities
