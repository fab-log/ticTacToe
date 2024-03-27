# ticTacToe
## Exercise from the MIT xPRO full stack developer course

This exercise brings the famous tic tac toe game into a web application.
Future improvements could be:

1. Stop the game as soon as one player wins. This could be solved by keeping track of the winner's state. Once there is a winner (`winO.length` or `winX.length > 0`) the onClick-event of the squares should be disabled.

2. Save the score of each player, so the players can play several times. To achieve this you could would first need to implement a reset functionality so the game can be restarted. In addition to that the score of each player needs to be stored in a variable which then could be displayed on top of the board.
