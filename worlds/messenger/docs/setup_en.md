# The Messenger Randomizer Setup Guide

## Quick Links
- [Game Info](../../../../games/The%20Messenger/info/en)
- [Settings Page](../../../../games/The%20Messenger/player-settings)
- [Courier Github](https://github.com/Brokemia/Courier)
- [The Messenger Randomizer AP Github](https://github.com/alwaysintreble/TheMessengerRandomizerModAP)
- [Jacksonbird8237's Item Tracker](https://github.com/Jacksonbird8237/TheMessengerItemTracker)
- [PopTracker Pack](https://github.com/alwaysintreble/TheMessengerTrackPack)

## Installation

1. Download and install Courier Mod Loader using the instructions on the release page
   * [Latest release is currently 0.7.1](https://github.com/Brokemia/Courier/releases)
2. Download and install the randomizer mod
   1. Download the latest TheMessengerRandomizerAP.zip from the
      [The Messenger Randomizer Mod AP releases page](https://github.com/alwaysintreble/TheMessengerRandomizerModAP/releases)
   2. Extract the zip file to `TheMessenger/Mods/` of your game's install location
      * You can have both the non-AP randomizer and the AP randomizer installed at the same time, but the AP randomizer
        is backwards compatible, so the non-AP one can be safely removed.
   3. Optionally, Backup your save game
      * On Windows
        1. Press `Windows Key + R` to open run
        2. Type `%appdata%` to access AppData
        3. Navigate to `AppData/locallow/SabotageStudios/The Messenger`
        4. Rename `SaveGame.txt` to any name of your choice
      * On Linux
        1. Navigate to `steamapps/compatdata/764790/pfx/drive_c/users/steamuser/AppData/LocalLow/Sabotage Studio/The Messenger`
        2. Rename `SaveGame.txt` to any name of your choice

## Joining a MultiWorld Game

1. Launch the game
2. Navigate to `Options > Third Party Mod Options`
3. Select `Reset Randomizer File Slots`
   * This will set up all of your save slots with new randomizer save files. You can have up to 3 randomizer files at a
     time, but must do this step again to start new runs afterwards.
4. Enter connection info using the relevant option buttons
   * **The game is limited to alphanumerical characters and `-` so when entering the host name replace `.` with ` ` and
     ensure that your player name when generating a settings file follows these constrictions**
   * This defaults to `archipelago.gg` and does not need to be manually changed if connecting to a game hosted on the
     website.
5. Select the `Connect to Archipelago` button
6. Navigate to save file selection
7. Select a new valid randomizer save

## Continuing a MultiWorld Game

At any point while playing, it is completely safe to quit. Returning to the title screen or closing the game will
disconnect you from the server. To reconnect to an in progress MultiWorld, simply load the correct save file for that
MultiWorld.

If the reconnection fails, the message on screen will state you are disconnected. If this happens, you can return to the
main menu and connect to the server as in [Joining a Multiworld Game](#joining-a-multiworld-game), then load the correct
save file.

## Troubleshooting

If you launch the game, and it hangs on the splash screen for more than 30 seconds try these steps:
1. Close the game and remove `TheMessengerRandomizerAP` from the `Mods` folder.
2. Launch The Messenger
3. Delete any save slot
4. Reinstall the randomizer mod following step 2 of the installation.