# ZombieDice

Created June 2019
Uploaded July 2021 

This Game Application, played in the console, allows the user to play the board game Zombie Dice with two to five players. The game will start by getting players’ names and then generates a random turn order.

How the game works:
- The game consists of 13 dice 
  - 6 Green Dice
    - Faces: 2xRunners, 3xBrains, 1xShots
  - 4 Yellow Dice
    - Faces: 2xRunners, 2xBrains, 2xShots
  - 3 Red Dice
    - Faces: 2xRunners, 1xBrains, 3xShots
- A player wins after she / he collects 13 brains and stops rolling.
- Turns alternate until there is a winner.
- Player turns
  -  A play has the following choices each turn
    -  Roll dice
      -  1. Gathering Dice
        - a. Runners are picked up
        - b. New dice are drawn until the player has 3 dice to roll or the zombie bucket is empty.
      - 2. Rolling Dice
        - a. Rolled brains are held
        - b. Rolled shots are held
        - c. Runners will be rerolled if the player continues.
      - 3. Check for death
        - a. If a player has 3 or more shots
          - His/her turn ends
          - All brains earned this turn are lost     
    - Stop
      - All brains gathered in the turn added the players score
      - If the player has 13 or more brains he / she wins the game.
