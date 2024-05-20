Name: Andy Nguyen

GitHub URL:
https://github.com/Andy-Nguyen4/GUI/blob/0d8bcb6f653bf0e8591b93035ff372c77a80909f/HW5/hw5.html


Link to GitHub Repository:
https://andy-nguyen4.github.io/GUI/


THE WRITE UP:


For this Scrabble board game, here are the features that are working:

Tallying Scores (with bonus squares): The game can tally scores correctly while also taking into consideration bonus square multipliers. There are two bonus squares. The score is also kept for multiple rounds and will update for each round until the player decides to restart the game.


Reshuffling, getting scores, and restarting: The player has the option to reshuffle the tiles on the tile rack (reshuffling), get the score, or start a new game. If the player chooses to play for multiple rounds, then the board will be cleared after each round, allowing the player to place new words. Restarting the game will clear the board (if there are tiles on it) and reset the score to zero. The player can restart the game anytime.


The program identifies which letter tile is dropped onto which Scrabble square: This can be viewed by looking at the console developer using the inspect element.
There are 7 Scrabble squares on the Scrabble board. It starts from square 0 and ends at square 6.
If you drop a tile into the first square, you’ll see this: Tile 'D' dropped onto square 0


Dragging tiles from the tile rack to the Scrabble board: The player can drag the tile from the tile rack and drop it into the Scrabble board. If the player drops it anywhere else, it will return to the tile rack.


Here are features that are working but are a bit buggy:


Dragging tiles from the Scrabble board back to the tile rack: You can drag the tiles from the Scrabble board back to the tile rack, however, when dropping the tile back into the tile rack, it makes duplicates of some other tiles.
For example, you place tiles ‘M’, ‘A’, and ‘D’ on the Scrabble board. You decide to move tile ‘A’ back into the tile rack. This works but it also makes duplicates of tiles ‘M’ and ‘D’ on the tile rack for some reason.


No letters can be placed on the same square: The game does not allow you to place more than 1 letter tile on each Scrabble square. If you try to place a new letter tile on an occupied Scrabble square, then the new tile will move back to the tile rack. While this feature works, it has the same issue as the feature above. Whenever a tile gets moved back to the rack, it duplicates some other tiles.