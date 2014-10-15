# Menu Info

The menu superclass contains methods and basic layout
templates for each subclass. The menu superclass will
automatically organize any subclass menu info into ASCII.


## Main Menu

The main menu will include the game title and play
options including singleplayer and  multiplayer.

Displays:
* Game Title
* Singleplayer (to gamemode menu)
* Multiplayer (to gamemode menu)

## Gamemodes Menu

The game mode menu will will ask the user how many
players and npc they want in the game as well as
which teams they should be on.

## Battle Menu

The battle menu will act as a HUD and allow the current
player character to choose there options.

The information provided will include:

HUD:
* Current Player
    * Jaeger or Kaiju Name
    * HP
    * optional info (part status, energy level, etc)
    * team name
* Team Player Status
    * Jaeger or Kaiju Name
    * HP
    * team name

Actions:
* Scan Battle Field (Shows enemy player status)
    * Target selection
        * list available targets
            * choose move
    * defend (self)
    * protect
        * list available tartget to protect
            * choose target

---
[Package Info]()
