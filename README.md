# Lone-Adventurer

## Project Description:

This is a turn-based RPG game similar to Darkest Dungeon, For the King, and Slay the Spire.  In this game the player will be forced to take on a battle against a monster in a turn-based scenario.  There will be an interactive map with each tile representing a different encounter.  The player will have to complete the given instance in order to continue and their health will persist between encounters.  When the health of the player is depleted, the game will be over and they will be brought back to the main menu.  Due to the nature of turn-based RPGS, more encounters and random events will increase replayability and variability of the environment.

## Project Files:
1. main.py
2. map.py
3. button.py
4. button2.py
5. battle.py
6. data.py
7. event1.py
8. inventory.py
9. images files
10.graphics files
11.music files
12.battle files
13.font files
14.readme.md
15.SRS Document
16.App executable "main"


## Install and Run the Project:
1. Install vscode on MacOS: https://code.visualstudio.com/docs/setup/mac
2. Install python on MacOS (Terminal): brew install python3
3. Install pygame on MacOS (Terminal): pip3 install pygame

4. Execute the program:
(1) On startup of the application, a main menu screen displays three options of “START”, “SETTINGS” and “QUIT” buttons. 
(2) The "Settings" menu can adjust the volume of background music.
(3) The user will also be able to “Quit” out of the application from the Main Menu. 
(4) Once the player enters the map from the start button to start the game, the player will be asked to choose the first tile they want to start on. Then the game event will initialize and the random encounter will begin.   
(5) The player will proceed in combat until the enemy health reaches 0 or the player has perished in battle. The player's force value and equipment will be displayed during the game process.
(6) In the map interface, the player can select the "QUIT" button to exit the game at any time.
