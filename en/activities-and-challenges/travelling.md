# Travelling

## Introduction

Stepping is the main mechanic in SimpleMMO, allowing players to earn gold, experience points, items, collect materials and fight NPCs without the use of energy. The travel screen features the `Step Button`, which the player can click to "take a step" starting a travel text or travel event.

## Travel Texts

For each step, the travel screen will have a chance to show different possible events. Stepping in specific **Locations** will change the rates of Travel Text, NPC encounter and Material Node rates. The default travel text on the travel screen displays: "_You emerge from the hole that you call your home and set off on your adventure._" Interactable texts such as NPC or material nodes do not need to be interacted with and can be skipped by clicking the step button once the cooldown is over.

For each step there is a chance for the player to receive an amount of gold or EXP.

All steps are followed by a cooldown on the step button, which can range from 4-9 seconds (hardcap is 3.5 seconds with active effects).

There are different possible events that may occur when stepping:

- Travel text; "_You take a step..._"

  - The travel screen displays a developer-approved travel text.

- Material Node

  - The travel screen displays a material node. Upon clicking it, the user is able to collect the material for the node. The top text changes depending on the type of material it is.
  - Harvesting the material contributes to [skills][1] EXP, which allows users to level up and access higher rarity materials.

- NPC Encounter

  - The player encounters any NPC below or a few levels above their current level.
  - The NPC depends on the location the player is travelling in.
  - From the travel screen, the player is able to 'attack' or 'view stats' of the NPC

- New player; You come across _player_ who is travelling right now.

  - The profile of a newly registered account is shown on the step screen
  - You are able to wave to the player from the text, or go to their profile.

- Item drop: You have found an item!

  - The player receives an item, which can be found in their inventory.
  - The item can be any rarity, and has a level between 1 and 8 levels above their current level.

  - Hold your horses!; "Woah steady on there. You're trying it too fast!"
    - The player has attempted to step before the step button cooldown has ended.
    - This text will not give you any EXP or gold.

- No health; "You're dead. You need to heal yourself before you can continue travelling."
  - You are unable to step as you have 0 health.
  - Clicking the button will show a popup with health information, and buttons taking the player to the shops or the healer in town.
  - This travel text awards no EXP or gold.

## Stepping Buffs
to be added;
(guild step buffs, potions, global boosts etc)

## Sprint

Sprint is a travel mechanic which allows the player to consume EP in exchange for a temporary +25% travel speed buff. 1 EP is equal to 1 minute of sprinting, and the sprint timer is shown on the step button to indicate the amount of time left of sprinting. You cannot add more time onto the sprint timer until it has ended. Sprint stepping speed buffs are able to stack with potion buffs.

## Travel Party

### Introduction
Travel Parties let you step together with up to 3 other players.
When other players are actively stepping, you have a chance to receive:
- A small amount of gold
- A small amount of player EXP

The rewards scale with your player level, and are not affected by other players’ levels. You will only receive the rewards if you are also actively stepping.

### Accessing Travel Parties
On the travel screen, you can click the `Party` button to access the travel party screen. The party screen shows your party (if you are in one), you friends' parties, and public travel parties. If you are not currently in a travel party, you are able to create one for yourself free of charge. The owner of a travel party is indicated by a crown icon beside their name.

### Editing Your Travel Party
If you are the owner of a travel party, you are able to choose to make the party private, or public (anybody can join from the party screen). Travel parties are private by default. Y

You can choose when inactive players get removed:
- 5, 10, 20, 30, 60 minutes
- 3, 6, 12 hours
- 1 day or 1 week

Inactive players show as greyed out, and they are auto-removed after the inactivity tim limit is reached. The party owner is NOT affected by AFK kick

### Managing Travel Parties
In public parties, a player can enter the party as long as there is less tha 4 players in it. You can find private parties by clicking on the profile of a person who is in the party, and requesting to join. 

The party owner is able to:
- View and accept/reject join requests
- Send party invites to people in their friends listR
- Receive (optional) in-game notifications when a player joins their party
- 
The party owner cannot join another travel party if they own one, and must delete it to join other parties. Additionally, a party cannot be renamed, so for a different name the party must be deleted and a new one created.

## Locations
Players are about to step in different locations, which offer different travel text, NPC encounter, and material node rates. For more information on these encounter rates, you may click the `view` button under each location in the locations page. The Horse and Carriage page can be found by clicking `Town`-> `Change Location`, or `Travel` -> `Change Location`.

<div class="table-container">
  
| Location                 | Level |
| ------------------------ | ----- |
| Simpletopia              | 1     |
| Holbeck                  | 5     |
| Davenport                | 10    |
| Ironforge                | 30    |
| Everwinter               | 50    |
| Elise Mountain           | 100   |
| The Underworld           | 150   |
| Desert of Eternal Dreams | 200   |
| Ednia                    | 250   | 
| Mount Byrior             | 300   | 
| Baththagnte Creek        | 350   |
| Saint Xvilhol            | 400   |
| New Bramp                | 450   |
| Lake Masmark             | 500   |
| Eldham                   | 550   |
| Mount Hawkfels           | 600   |
| Old Ranhor               | 650   |
| Venzor                   | 700   |
| Dragontail               | 800   |
| Arkhan                   | 900   |


</div>

During some events, event specific locations become available. They have their own set of NPCs and will also drop Elite and Common tier Event Material Nodes, and have a level requirement of 1.

<div class="table-container">
  
| Event Location          | Event             |
| ----------------------- | ----------------- |
| Spooky Graveyard        | Halloween         |
| North Pole              | Christmas         |
| The Land of Broken Eggs | Easter            |
| Planes of Alangar       | Gods of SimpleMMO |
| Love Island             | Valentines        |
| Community Island        | Community Event   |
| Memory Lane             | Memory Lane       |
| Lunar Blossom Vale      | Lunar New Year    |


</div>

[1]: /wiki/character/skills?same_window=true
