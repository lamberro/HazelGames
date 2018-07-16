# HazelGames
version 2

A Project by Ross Lambert

## Description
Do you ever have trouble thinking of what to play? This program makes choosing games marginally easier by limiting your selection down to only games with a valid number of players! Huzzah!

When booting the program, the program will list out registered users from Preferences.txt, if any are registered on that document. Wait until the program says "Number of players: ". When this happens, simply write any integer you want and press enter, and the program will list all of the valid games out for you.

## Changes in Version 2
* HazelGames now comes with Preferences.txt, where users can register a list of game preferences or opinions! These opinions will show up beside any game that is listed.

## Requirements
If the program is taking an unreasonable amount of time to display the message "Number of players: ", then the requirements might not be met.

### Games.txt Requirements
* The file "Games.txt" must be in the same folder as "HazelGames.exe".
* Games should be listed as "Game_Name minimum_number_of_players maximum_number_of_players" (e.g. Settlers_of_Catan 2 6)
* Game titles cannot have spaces. Use underscores instead.
* Numbers of players must be positive integers
* The program does not read line by line, so if you really wanted to you could list all games in a single line.

### Preferences.txt Requirements
* the file "Preferences.txt must be in the same folder as "HazelGames.exe"
* The format for this file is as follows: A username is provided in angle brackets (e.g. <USERNAME>). After the username, list games as one word, with each game being on a new line. On games on which you wish to leave an opinion, write an opinion in quotes on the same line as the game's title. The title must be left of the opinion. An example file is provided.
* You do not need to include every game that is in Games.txt, however all games that you include in Preferences.txt must also be included in Games.txt.
* Game titles cannot have spaces or begin with the < symbol

## Possible Future Improvements
* A random selector, which would choose a game for the user based on the number of players.
