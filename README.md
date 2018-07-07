# HazelGames
version 1

A Project by Ross Lambert

## Description
Do you ever have trouble thinking of what to play? This program makes choosing games marginally easier by limiting your selection down to only games with a valid number of players! Huzzah!

When booting the program, wait until the program says "Number of players: ". When this happens, simply write any integer you want and press enter, and the program will list all of the valid games out for you.

If the program is taking an unreasonable amount of time to display the message "Number of players: ", then the requirements might not be met.

## Requirements
* The file "Games.txt" MUST be in the same folder as "HazelGames.exe".
* Games should be listed as "Game_Name minimum_number_of_players maximum_number_of_players" (e.g. Settlers_of_Catan 2 6)
* Game titles cannot have spaces. Use underscores instead.
* Numbers of players must be positive integers
* The program does not read line by line, so if you really wanted to you could list all games in a single line.

##possible improvements
* Some sorting system. Currently, games are sorted by their appearance in "Games.txt". In later installments, a "score" of some sort could be applied to games and added to "Games.txt".
