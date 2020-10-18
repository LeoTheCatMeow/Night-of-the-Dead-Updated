# Night of the Dead Updated

Disclaimer: I take no credit for the base game. This is only a personal attempt to bugfix and keep the game up and running smoothly in SC2 Arcade, with potential QOL or community requested updates. There may be a small amount of experimental features and personal explorations, but I will do my best to keep the game stable.

# Changelog
For list of latest changes see [changelog](CHANGELOG.md)

# Requirements
1. StarCraft II account (Starter Edition will open the map, but will not let testing it)

# Installation
1. Place bin/src folders in "Mods\Night of the Dead" in StarCraft II install folder (e. g. "C:\Program Files (x86)\StarCraft II\Mods\Night of the Dead"). Create "Mods" folder if necessary.
2. Launch "Mods\Night of the Dead\src\NOTD.SC2Map\ComponentList.SC2Components" to open map in editor. File associations may not work for first run, so be sure to open it with SC2Edit.

# Tips
1. To make map load faster, change Editor startup settings to load triggers module instead of terrain in File -> Preferences -> Startup.
2. Place your SC2Bank file in "Documents\StarCraft II\Banks" to use it in test mode.
3. While in test mode additional Editor cheats can be used for convenience. For full reference see [docs/SC2TestDocumentCheats.txt](docs/SC2TestDocumentCheats.txt), copy pasted from [patch 1.3.0 notes](https://news.blizzard.com/en-us/starcraft2/2514162/patch-1-3-0-now-live). Common cheats:
	* god - Turns on god mode for the selected player.
	* showmap - Toggles fog of war display and validation.
	* makeunit chain - Creates XM814 Heavy Machine Gun at cursor.
	* makeunit ammo 5 - Creates 5 ammo boxes at cursor.
	* makeunit eos 1 14 - Creates 1 Eos for player 14 at cursor.
	* deathunit - Kills the selected units.
	* move - Moves the selected units to the cursor position.
	* xp 10000 - Adds 10000 XP to the selected units.
4. Triggers can be manually run with TrigRun, however correct identifier needs to be used. To run Sec B Hades fight trigger named "STW16b - Boss Fight (Hades)" type "trigrun STW16bBossFightHades". Correct identifier can be found by right clicking trigger and selecting 'Element Properties...', or highlighting a trigger and pressing Ctrl+Enter.
5. For testing purposes it may be useful to disable certain story/world triggers, like ambient spawns.
