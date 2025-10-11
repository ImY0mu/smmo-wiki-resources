# Travelling

to do

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

## Sprint

Sprint is a travel mechanic which allows the player to consume EP in exchange for a temporary +25% travel speed buff. 1 EP is equal to 1 minute of sprinting, and the sprint timer is shown on the step button to indicate the amount of time left of sprinting. You cannot add more time onto the sprint timer until it has ended. Sprint stepping speed buffs are able to stack with potion buffs.

## Travel Party

Travel parties is a mechanic where you are able to step in a group of up to 3 other players. When other players are _actively_ stepping, there is a chance of you receiving a small percentage of gold or player EXP. The amount of gold/exp distributed scales to your personal level and is not affected by the levels of other players. You will only receive the gold and EXP if you are also actively stepping.

On the travel screen, you can click the `Party` button to access the travel party screen. The party screen shows your party (if you are in one), you friends' parties, and public travel parties. If you are not currently in a travel party, you are able to create one for yourself free of charge. The owner of a travel party is indicated by a crown icon beside their name.

If you are the owner of a travel party, you are able to choose to make the party private, or public (anybody can join from the party screen). Travel parties are private by default. You can also set an inactivity kick for 5, 10, 20, 30, 60 minutes, 3, 6, 12 hours, and 1 day or a week. Inactive steppers have a 'greyed out' icon on the step screen, and will automatically be removed from the party when they have not been stepping for the set amount of time. The owner can also manually remove a player from their party, and the AFK kick does not affect the owner.

In public parties, a player can enter the party as long as there is less tha 4 players in it. You can find private parties by clicking on the profile of a person who is in the party, and requesting to join. The party owner is able to view and accept/reject join requests, and send party invites to people in their friends list. The owner receives an (optional) in-game notification when a player joins their party. An owner cannot join another travel party if they own one, and must delete it to join other parties. Additionally, a party cannot be renamed, so for a different name the party must be deleted and a new one created.

## Locations

[1]: /wiki/character/skills?same_window=true
