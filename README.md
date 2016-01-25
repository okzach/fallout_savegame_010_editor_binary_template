# Fallout 4 Save Game Binary Template

A `binary template` describing `Fallout 4` save game files `(*.fos)`, for use with `010 Editor`.

## About

Fallout 4 save games are binary files using the extension `*.fos`.  Every time you save the game, it creates a new `.fos` file.  By default these are stored in `%USERPROFILE%\Documents\My Games\Fallout4\Saves\*.fos`.

This template enables `010 Editor` to inspect the contents of these files.

Each save file starts with the players name, level, location, and play time.  Later in the file are 87 statistics, including the number of quests completed for each faction.

## History

This project was last updated in January of 2016.

At that time the following was true:

* `Fallout 4` was at version `1.2.37.0`.
* `010 Editor` was at version `6.0.3`.
