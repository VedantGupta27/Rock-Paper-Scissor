
//Rock Paper Scissors Game
//This is a simple Rock Paper Scissors game built with HTML, CSS, and JavaScript.


How to Play
Click on one of the three choices: Rock, Paper, or Scissors. The computer will randomly make a choice, and the winner will be determined based on the classic game rules. The score is tracked on the scoreboard.


File Structure
The project consists of three main files:

index.htm: The main HTML file that sets up the game's structure, including the title, choices, scoreboard, and message area.

style.css: The CSS file that handles the styling and layout of the game, including colors, fonts, and arrangement of elements.

app.js: The JavaScript file that contains all the game logic. It handles user input, generates the computer's choice, determines the winner, updates the score, and displays the game results.


Game Logic (app.js)
userScore and compScore: These variables track the scores for the player and the computer, respectively.
choices: This variable selects all the choice elements (Rock, Paper, Scissors) from the HTML.
genCompChoice(): This function randomly generates the computer's choice from an array of "rock," "paper," and "scissors."
drawGame(): This function is called when the user and computer choices are the same. It updates the message to "Game was Draw."
showWinner(userWin, userChoice, compChoice): This function is called to display the result of the game.
If userWin is true, the user's score increases, and a green "You win!" message is displayed.
If userWin is false, the computer's score increases, and a red "You lost." message is displayed.
playGame(userChoice): This is the core function that orchestrates each round.
It takes the user's choice as an argument.
It calls genCompChoice() to get the computer's move.
It checks for a draw or determines the winner based on the game's rules.
It calls drawGame() or showWinner() to update the game state.
Event Listener: An event listener is added to each choice element. When a choice is clicked, it calls the playGame() function with the selected choice's ID.








add how to play instructions


Rock Paper Scissors Game
This is a simple Rock Paper Scissors game built with HTML, CSS, and JavaScript.

How to Play
Click on one of the three choices: Rock, Paper, or Scissors. The computer will randomly make a choice, and the winner is determined based on the classic game rules. The scores for you and the computer are tracked on the scoreboard, and the game outcome is displayed in a message.

File Structure
The project consists of three main files:

index.htm: The main HTML file that sets up the game's structure, including the title, choices, scoreboard, and message area.

style.css: The CSS file that handles the styling and layout of the game, including colors, fonts, and arrangement of elements.

app.js: The JavaScript file that contains all the game logic. It handles user input, generates the computer's choice, determines the winner, updates the score, and displays the game results.

Game Logic (app.js)
userScore and compScore: These variables track the scores for the player and the computer, respectively.

choices: This variable selects all the choice elements (Rock, Paper, Scissors) from the HTML.

genCompChoice(): This function randomly generates the computer's choice from an array of "rock," "paper," and "scissors".

drawGame(): This function is called when the user and computer choices are the same and updates the message to "Game was Draw".

showWinner(userWin, userChoice, compChoice): This function is called to display the result of the game. If userWin is true, the user's score increases, and a green "You win!" message is displayed. If userWin is false, the computer's score increases, and a red "You lost." message is displayed.

playGame(userChoice): This is the core function that orchestrates each round. It takes the user's choice as an argument, calls genCompChoice() for the computer's move, checks for a draw or determines the winner, and calls drawGame() or showWinner() to update the game state.

Event Listener: An event listener is added to each choice element. When a choice is clicked, it calls the playGame() function with the selected choice's ID.
