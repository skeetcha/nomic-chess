# Nomic Chess
A game of Nomic Chess, that is, Chess combined with the game Nomic

# Structure of Files

## Blank Game Template
A blank game template is included in [game-template](game-template/). The initial set of rules, the board templates, and anything else needed to play Nomic Chess are contained in that folder. When starting a new game, create a new branch (or fork) and copy the contents of that folder into the root.

## Playing the Game
Follow the rules while playing the game (obviously). All players must have commit access while playing the game (it may be removed when the game is over).

### The Player List
Create a file called `player-list.md` at root. Add all players names and include numbers by their names. This will indicate what armies they control (which is only their base army at the beginning of the game) and will be updated as the game goes along.

### Making Rule Changes
To make a rule change, a rule proposal document must be submitted in `rules/` detailing the change and include a list of each player's name on the player list. Commit and push the file to the repo. Each player must then either edit in a Y or an N next to their name indicating whether or not they approve or reject the rule respectively. Once a rule change has passed in accordance with the current rules, the player who proposed the rule must then add the rule file with the appropriate number as well as update the table of contents file. Commit the file changes and push.

### Moving a Piece
To move a piece, edit the files necessary and commit and push the changes. Only move pieces you are legally allowed to move.

### Capturing an Army
When a player captures an army, edit the player list document (`player-list.md`) to reflect that they have a new army. If a player ever loses their last army, edit their name to have strikes through it or otherwise denote them as being out of the game.

## Archives
Once a game in the main repository is finished, the folders created for the game will go into a folder in [archives](archives/). If you are playing a game of Nomic Chess on a fork or a branch and would like to add your game to the archives, simply make sure your folder is named something other than game-# (this is the format used for archived games) under archives and submit a pull request. Pull requests not following this format will be rejected immediately.

## Game Structure
When there is a game in play, here are some of the folders that you can find in play.

### Rules
The current ruleset for the current game of Nomic Chess being played can be found in `rules/`.

### Boards
The current set of half-boards for the current game of Nomic Chess being played can be found in `boards/`.
