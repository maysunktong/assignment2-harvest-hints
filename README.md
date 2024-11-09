Note: Turn on **'Inspect'** to see `Key answer`

![CleanShot 2567-11-07 at 22 23 01@2x](https://github.com/user-attachments/assets/ccff3814-92d6-4e68-b62e-ae0c255d9814)

## Game flow
Harvest Hints is handled by two main functions: `startGame()` and `playGame()`
`startGame()` - handle name input and game options leading to main gameplay or `playGame()`
1. Game initialization
- User inputs name
- User choose options [0] & [1] to go further to category prompt(`playGame()`) or change name (restart `startGame()`)
2. Main Gameplay
- User's max attempts is reset
- User will choose a category in a prompt
- User will guess a word based on the category chosen
- Each guess is evaluated. Left attempt decreases.
- Evaluate a game: win or lose
- On evaluation modal (`confirm()`), user can choose to replay or exit game.
