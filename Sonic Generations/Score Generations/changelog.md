## Score Generations - Version 1.4.6
- Fixes for HE1ML.

## Score Generations - Version 1.4.5
- Implemented E rank requirements for custom HUDs.
- Fixed irregularities with Restore Last Checkpoint Score when restarting the stage whilst dead.

## Score Generations - Version 1.4.4
- Fixed results progress bar appearing empty if the player finishes with zero rings.

## Score Generations - Version 1.4.3
- Fixed time computation returning zero (this should fix your final score being lower than expected with the time bonus).
- Added max velocity to the API for returning the highest recorded velocity in the stage.

## Score Generations - Version 1.4.2
- Fixed the ring count not persisting in results for custom HUDs using BlueBlur.
- Fixed the game crashing when defeating a boss after backing out of a stage.

## Score Generations - Version 1.4.1
- Fixed the game crashing when loading into a stage with Restore Last Checkpoint Score enabled.
- Fixed score resetting to zero when dying at a checkpoint, despite Restore Last Checkpoint Score being enabled.

## Score Generations - Version 1.4
- Implemented trick bonus per direction, multiplying when you change direction and resetting when you keep using the same direction.
- Changed the multipliers to use floats instead of integers to support non-whole bonus multiplication.
- Changed the timers to use floats instead of integers for more precise timing between deltas.
- Implemented additional API functions for third-party mods to utilise (see the [wiki](https://github.com/HyperBE32/App-Extension-Mods/wiki/Score-Generations#using-the-api) for more details).

## Score Generations - Version 1.3.5
- Implemented an API for mod developers to use to access Score Generations functions from external DLLs. Please update for support with future mods.
- Implemented S rank requirements for custom HUDs.
- Reimplemented the ring bonus progress bar in the results screen.
- Stages that don't have rank tables will now be marked as forbidden, allowing Gens' default score system to be used instead.
- The Lua engine will now fall back on the last loaded Lua script instead of the default Score Generations one if a mod of higher priority doesn't have a Lua script.
- Fixed score counter displaying zero after hitting the goal plate as Classic Sonic.

## Score Generations - Version 1.3.4
- Server migration... Congratulations, you made it through!

## Score Generations - Version 1.3.3
- Added configurable clamp to homing chain and slam bonuses to prevent absurd score bonuses for custom stages.

## Score Generations - Version 1.3.2
- Fixed incorrect result animations when the player finishes without a perfect bonus.

## Score Generations - Version 1.3.1
- Renamed instances of 'velocity bonus' to 'speed bonus' to better represent the result from Sonic Unleashed.

## Score Generations - Version 1.3
- Added option to toggle velocity bonus.
- Added option to restore your last score from a checkpoint.
- Exposed the velocity bonus multiplier to the configuration.
- Trick finishes now increase the total tricks counter.
- All statistics now reset correctly when necessary.

## Score Generations - Version 1.2.2
- Security update for Lua callback.

## Score Generations - Version 1.2.1
- Improved No Trick Rainbow Rings detection by removing it and rewriting the patch (**UPDATE YOUR COMMUNITY CODES**).

## Score Generations - Version 1.2
- Fixed progress bar going slightly over the rank you achieved.
- Exposed a ton more totals to Lua for mod developers.
- Increased ranks for Seaside Hill and Rooftop Run.
- Added options for perfect bonus (you can now only get a perfect bonus for A ranks by default).

## Score Generations - Version 1.1.1
- Improved time bonus calculation.
- Readjusted the rank tables to account for the improved time bonus.
- Added configurable score time-out like Sonic Colours.
- Added user algorithm for mod developers to execute their own non-descript Lua functions.
- Added print function to Lua.
- Exposed the stage ID to Lua.

## Score Generations - Version 1.1
- Fixed the No Trick Rainbow Rings code not rewarding score for rainbow rings.
- Implemented homing chain and slam bonuses.

## Score Generations - Version 1.0.4
- Fixed configuration schema writing to the incorrect parameter for trick combos.

## Score Generations - Version 1.0.3
- Fixed quick stepping not giving you score.

## Score Generations - Version 1.0.2
- Fixed configuration schema writing to the incorrect section for score.
- Moved comments in the configuration above the sections to fix an issue with Hedge Mod Manager adding them to the section names.

## Score Generations - Version 1.0.1
- Improved support with other mods using score configurations.

## Score Generations - Version 1.0
- First release of Score Generations!
