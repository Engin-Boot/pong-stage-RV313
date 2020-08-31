# Displaying Winners

## Category I

This Module will show us Top Players of the Week.

### Scenario : Player user want to see Top 10

Given : We have no game in progress and internet connection is ON.

When : We select the Leadership board of Top 10 players.

Then : Display the Top 10 Players sorted by coins.

### Scenario : Player want to see Top 100

Given : We have no game in progress and internet connection is ON.

When : We select the Leadership board of Top 100 players.

Then : Display the Top 100 Players sorted by coins.

## Category II

This module will show the result of the recently played game.

### Scenario : Checking for winner for a offline game

Given : The game running on system and the game is just finished and played offline.

When : The score reaches 10 points.

Then : Display the player_ID who reaches 10 points first.

### Scenario : Checking for winner for a online game

Given : The game running on system and its finished and played online with Internet is ON.

When : The score reaches 10 points.

Then : Display the player_ID who reaches 10 points first.
