# Travelling
to do

## Introduction
Stepping is the main mechanic in SimpleMMO, allowing players to earn gold, experience points, items, collect materials and fight NPCs without the use of energy. The travel screen features the `Step Button`, which the player can click to "take a step" starting a travel text or travel event. 

## Travel Texts
For each step, the travel screen will have a chance to show different possible events. Stepping in specific **Locations** will change the rates of Travel Text, NPC encounter and Material Node rates. The default travel text on the travel screen displays: "*You emerge from the hole that you call your home and set off on your adventure.*" Interactable texts such as NPC or material nodes do not need to be interacted with and can be skipped by clicking the step button once the cooldown is over.

For each step there is a chance for the player to recieve an amount of gold or EXP.

All steps are followed by a cooldown on the step button, which can range from 4-9 seconds (hardcap is 3.5 seconds with active effects). 

There are different possible events that may occur when stepping:
- Travel text; "*You take a step...*"
  - The travel screen displays a developer-approved travel text.

- Material Node
  - The travel screen displays a material node. Upon clicking it, the user is able to collect the material for the node. The top text changes depending on the type of material it is.
  - Harvesting the material contributes to [skills][1] EXP, which allows users to level up and access higher rarity materials.
 
- NPC Encounter
  - The player encounters any NPC below or a few levels above their current level.
  - The NPC depends on the location the player is travelling in.
  - From the travel screen, the player is able to 'attack' or 'view stats' of the NPC
 
- New player; You come across *player* who is travelling right now.
  - The profile of a newly registered account is shown on the step screen
  - You are able to wave to the player from the text, or go to their profile.
 
- Item drop: You have found an item!
  - The player recieves an item, which can be found in their inventory.
  - The item can be any rarity, and has a level between 1 and 8 levels above their current level.
 
  - Hold your horses!; "Woah steady on there. You're trying it too fast!"
    - The player has attempted to step before the step button cooldown has ended.
    - This text will not give you any EXP or gold.

- No health; "You're dead. You need to heal yourself before you can continue travelling."
  - You are unable to step as you have 0 health.
  - Clicking the button will show a popup with health information, and buttons taking the player to the shops or the healer in town.
  - This travel text awards no EXP or gold.
    
## Stepping Buffs

## Sprint

## Travel Party

## Locations


[1]:/wiki/character/skills?same_window=true
