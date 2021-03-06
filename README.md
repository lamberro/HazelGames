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
* The spaces between data inputs can be tabs, spaces, or new lines.
* Numbers of players must be positive integers
* The program does not read line by line, so if you really wanted to you could list all games in a single line.

### Preferences.txt Requirements
* the file "Preferences.txt must be in the same folder as "HazelGames.exe"
* the file must end in \<end>
* Users cannot have the name \<end>
* The format for this file is as follows: A username is provided in angle brackets (e.g. <USERNAME>). After the username, list games as one word, with each game being on a new line. On games on which you wish to leave an opinion, write an opinion in quotes on the same line as the game's title. The title must be left of the opinion. An example file is provided.
* You do not need to include every game that is in Games.txt, however all games that you include in Preferences.txt must also be included in Games.txt.
* Game titles cannot have spaces or begin with the < symbol.
* As with Games.txt, you do not have to separate things by line, but I would recomment it for readability. Between all data entries, you can have any number of spaces, tabs, or new lines, so long as there is at least one of those.

## Possible Future Improvements
* It would be nice if a user could turn off the opinions of some opinions if they belong to users who aren't going to be playing the game with the current user. For example, the ability to select or deselect different users depending on who is using the program, or maybe the ability to switch out Preferences.txt files depending on who is using the program. 
* A random selector, which would choose a game for the user based on the number of players.
* An ability to sort games by genre
