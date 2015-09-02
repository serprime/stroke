# stroke
touch typing game for programmers

## overview

java webserver:
- deliver javascript based client to play the game
- offer rest api to get levels and post results
- spring boot web + jpa

database:
- to store results and rank of players

javascript client
- react based ui

java terminal client
- cli based client to play the game

## to decide

shall we store levels in the database or are they hardcoded?

## for developers/programmers

besides standards word of the english? language, we need lots of keywords of programming languages and lots of brackets, special characters, number, camelCased words, ...

ultra hard mode is just random words of all available characters.


## Ideas


### tag: optimizedfor 80x24

in the cli client, print somewhere "optimized for 80x24"


### Everything is a character

instead of points or lives of the player, we use characters that get removed/collected/...

### survival

player has some characters (as lives) and can play until she mistyped the number of characters available

### multiplayer

- play against an opponent until some one mistypes once.
- get instant feedback about where the opponent is (to stress the player)
