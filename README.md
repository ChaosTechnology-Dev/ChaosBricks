# ChaosBricks
A game about blocks, chaos and explosions.  
You can find the download link for all versions in the [releases section](https://github.com/ChaosTechnology/ChaosBricks/releases).

Join our [Discord](https://discord.gg/97beRG6EJb) server!

Support us on [Patreon](https://www.patreon.com/chaostechnology)?

## The Concept
ChaosBricks is a puzzle game based on stacking blocks and solving lines in which you can play and create in whichever way you like.  
The game is customizable in just about any way imaginable, from the blocks you play with to the scoring conditions, and if that's not enough you can even add custom scripts to further enhance your mode.  
There are basically no limits to your creativity.  

## Items
The game features over 50 unique items that can greatly impact gameplay.  
The effects range from explosions and fire to controlling an enemie's block or even creating life.  
An extensive list with tutorials can be found in-game, explaining each item in detail, complete with a demonstration video.  
Items are added via scripts. For instance, the default mode adds items as a reward for erasing a line.  

## The Main Menu
![main menu][imgMainMenu] 
| Button | Function |
| :---------------- | :------------------------------- |
| Continue          | Start off where you last left the game. The number and profiles of players and the team configuration will be preserved as well as the selected game mode. |
| New Session       | Opens a game mode dialog and starts a new session with one random player and the newly selected game mode. |
| Tutorial          | Opens the the tutorial page. |
| Settings          | Opens the settings page. |
| Exit              | DANGER ZONE! This will end the game! |

## The Session Room
When you start a session of ChaosBricks, you will find yourself in a room in which you can add and arrange playing fields. Each player chooses their preferred controls (it's just 5 inputs, don't worry) and hits their assigned input for rotation to be "ready". Once every player is "ready", the chaos begins.
You can choose to play alone, together with, or against other players locally.  
When currently not playing, you can drag and drop the fields around using the blue anchors. You can also lock fields together by overlaying their anchors and right clicking them. Right click again to unlock.

![session room][imgSessionRoom]  
| Button                         | Function |
| :----------------------------: | :------------------------------- |
| ![exit][imgSessionExit]        | Leave the current session and return to the main menu. Any running games will be stopped. |
| ![exit][imgSessionTutorial]    | Opens the tutorial page. |
| ![exit][imgSessionGamemode]    | Opens the game mode editor. |
| ![exit][imgSessionTeamMgr]     | Opens the team manager. |
| ![exit][imgSessionSettings]    | Opens the settings page. |
| ![exit][imgSessionAddPlayer]   | Adds a new playing field to the session. |
| ![exit][imgSessionMultiScreen] | Enters multi-screen mode. Screens can be "closed" individually using the x-Button in the top right corner. This feature is experimental. |

## Team Manager
| ![team manager][imgTeamManager]  | ![teams in a session][imgTeamManagerFields] |
| :---------------- | :------------------------------- |
| In this dialog you can move players to teams and change the team names and colors. For simple PvP setups, you likely won't need to open this at all. | Team members with more than one member in their team will have their team name displayed, as well as their team's score next to their own. |

## Game Mode Editor
| Page | Description |
| :---------------------------------------- | :------------------------------- |
| ![description][imgGameModeDescription]    | This is the page you will see when you open the dialog. Here you can describe your mode with a short name and an extensive description of what players will do. You can also click the thumbnail to choose your own image for your mode.  |
| ![general][imgGameModeGeneral]            | Under the roles tab, you will be able to add and remove roles from your mode. In the team manager, you can assign a player to a specific role, meaning their according settings such as item settings and field bounds will apply to them. On the "General" page, you can choose a name for the role, the field dimensions, speed settings, as well as the starting appearance of the field. |
| ![items][imgGameModeItems]                | Here you can assign the weight and target of each item. The weight affects the chance of each item to be selected when chosen randomly. You can click the icon to edit item specific settings or view its tutorial. |
| ![item setting][imgGameModeItemSetting]   | Some items have specific settings that you can set here. The effect of each setting will be explained next to it. |
| ![item tutorial][imgGameModeItemTutorial] | If you are unsure how an item works, you can view its tutorial here as well. This is the same as in the tutorials page. |
| ![scoring][imgGameModeScoring]            | Here you can choose how many points a player earns for certain actions. Note that you can also give points via script. |
| ![scripting][imgGameModeScripting]        | Here you can add, remove and edit scripts assigned to your mode. For a detailed explanation, see the "Scripting" page in the tutorial dialog. You can also view and edit these scripts in the in-game console. |
| ![blocksets][imgGameModeBlocksets]        | Here you can draw the blocks that will be available for play. A mode can have multiple block sets, while each block set can contain any number of blocks. Whenever a block is queued, a random block will be selected from the player's current block set. The player's current block set can be changed via script. For instance, the "BlockSetCycle" default script does just that. |

## Settings
|  |  |
| :---------------- | :------------------------------- |
| ![settings][imgSettings]   | Here you can change settings regarding anything non-gameplay-related, such as graphics resolution and sound volume. These are the same settings as found in the settings.ini file in your local game directory. Credits and licenses can also be found here. |

## Tutorial
| Page | Description |
| :---------------------------------------- | :------------------------------- |
| ![general][imgTutorialGeneral]            | This page explains the very basics. You can click the videos to play them and see a demonstration. |
| ![items][imgTutorialItems]                | This page contains a list with all items. Click their icons to view a detailed description along with a demonstration video. |
| ![scripting][imgTutorialScripting]        | This page serves as a scripting tutorial and documentation. You can view all available types and events, as well as browse some examples. |


[imgMainMenu]:                 https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/MainMenu.png
[imgSessionRoom]:              https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20-%20Buttons.png
[imgTeamManager]:              https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/TeamManager.png
[imgTeamManagerFields]:        https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/TeamManager%20-%20Gameplay.png
[imgGameModeBlocksets]:        https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20Blocksets.png
[imgGameModeDescription]:      https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20Description.png
[imgGameModeGeneral]:          https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20General.png
[imgGameModeItems]:            https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20Items.png
[imgGameModeItemSetting]:      https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20ItemSetting.png
[imgGameModeItemTutorial]:     https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20ItemTutorial.png
[imgGameModeScoring]:          https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20Scoring.png
[imgGameModeScripting]:        https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20Scripting.png
[imgSettings]:                 https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/GameMode%20-%20Scripting.png
[imgTutorialGeneral]:          https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Tutorial%20-%20Main.png
[imgTutorialItems]:            https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Tutorial%20-%20Items.png
[imgTutorialScripting]:        https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Tutorial%20-%20Scripting.png
[imgSessionExit]:              https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/exit.png
[imgSessionGamemode]:          https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/gamemode.png
[imgSessionMultiScreen]:       https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/multiscreen.png
[imgSessionAddPlayer]:         https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/new%20player.png
[imgSessionSettings]:          https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/settings.png
[imgSessionTeamMgr]:           https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/team.png
[imgSessionTutorial]:          https://github.com/ChaosTechnology/ChaosBricks/blob/main/Images/Session%20Buttons/tutorial.png
