# gamemode_stop
Stops gamemode after a specified program is closed, preventing it from running in the background even when the game is stopped
This version is compatible with Stem and other launchers.

### $ gamemode_stop < game_name >
## With Steam. Ex:
### gamemode_stop < game_name > %command%

The "game_name" can be obtained by monitoring the Monitor process of your system, I recommend that you use "pidof" to validate the "game_name" (if it returns the PID it is correct).

About gamemode: https://github.com/FeralInteractive/gamemode

