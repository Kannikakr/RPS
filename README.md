# Rock_paper_scissors

1.User and Computer Scores:
Two variables, userScore and compScore, track the player's and computer's scores.

2.Game Elements:
choices represents the clickable elements (rock, paper, scissors), while msg displays messages about game results.
userScorePara and compScorePara show the updated scores.

3.Generating Computer Choice:
The function genCompChoice() randomly selects a choice (rock, paper, or scissors).

4.Handling a Draw:
drawGame() updates the message and styles when both the player and computer make the same choice.

5.Showing the Winner:
showWinner(userWin, userChoice, compChoice) updates the score and displays whether the user won or lost, along with the corresponding background color.

6.Playing the Game:
playGame(userChoice) compares the player's choice with the computer's and decides the winner.

7.Event Listeners:
The forEach loop attaches click event listeners to the choices, calling playGame() with the user's selection.
