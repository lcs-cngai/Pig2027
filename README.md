#  Pig

You against another player. Roll the dices and you roll a number. If you roll a 1, your turn ends and the game automatically gives the other player a new turn. The goal is to be the first one to have a total score of 100. The maximum rolls allowed are 6 per turn. If you are left with 0 remaining turns, your turn ends.

## How to Play

1. Click **Roll**
2. Once you roll a number (that is not 1), you can either hold your current score to be safe, or you can risk further by rolling again.
3. If you roll a 1, the turn ends and a new turn automatically goes to the other player
4. The maximum rolls allowed are 6 per turn. If you are left with 0 remaining turns, your turn ends.
5. The other player gets a new turn and the remaining turns are resetted back to 6.

## Testing

|Test|Chosen Input|Should happen|Did happen|
|Points erased when a player's turn ends by rolling 1 or running out of turns|Remaining Turns = 0; Score resets to 0; Switch Turns|-|-|
|One roll counts down|Roll fixed at 2; Player 1 clicks Roll once|Remaining turns: 5, and the turn total is 2|✅|
| | | | |
| | | | |
| | | | |


## What I added

I modified the game by creating a limit of 6 rolls per turn. This is to prevent a player from getting too many points from an extremely high roll streak without getting a 1. I also made the rule that when a playe's turn ends, the other player gets a new turn and the remaining rolls are resetted back to 6. The same rules from the original game apply when you roll a 1.

## Credits

Cody NGAI
