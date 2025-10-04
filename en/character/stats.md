# Stats

## Introduction

In SimpleMMO, each character is described by three main stats: strength (str); defence (def); and dexterity (dex). During combat, the two combating characters’ stats are compared in a series of calculations. The game then rolls for damage dealt based on the outcome of these calculations. Additionally, dex alone is used to determine the chance of completing a [quest](https://simplemmo.fandom.com/wiki/Quests). Stats can be boosted by leveling up, purchasing equipment, and having a profession with a stat bonus.

### Levelling Up

Player will recieve 2 stat points for every level up. These can be applied to your character's stats at the Character page.

### Equipment

You can use [equipment][1] to boost your stats by a large amount. Equipment comes in diffrent [rarities][2] and they all provide different stats.

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

## A comment to defence

Defence is sometimes an underrated stat because of the high use of crit gear who has mostly very low defence wich more of the higuer levels didn't need mostly, but it really have a high impact on regular players:
What give you the defence stat? It is a combination of Armor who reduces directly the damage you take from other players or npcs and also give the chance of the enemy to miss attacks
You could ask yourself if this really make a worthy impact enough for you to quit str to invest on defence or byy gear with more defence.
As a pvp enjoyer i can ashure defence is extremely useful being actively playing and also when you go offline (there will be less chances you get killed by lower levels or mabe higher ones with not enough dexterity) Also it helps when you are stabbing and you have to stop less to refill heal for fighting players near your level. (sometimes i have defeated players with 10k more levels just because i have enough defence to make it fail the hits enough) also if you dont like to step much but like pvp defence will be way more worth for you than strength.


[1]:/items/item-types
[2]:/items/rarities
