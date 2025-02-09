# rock_paper_scissors
This Rock-Paper-Scissors game takes user input, randomly selects a choice for the computer, and compares both to determine the winner. It then prints either "You win!" or "You lose!" along with the computer’s choice. 🎮
#  standard Rock-Paper-Scissors rules
* Rock (0) beats Scissors (2)
* Paper (1) beats Rock (0)
* Scissors (2) beats Paper (1)
* If both the user and the computer choose the same option, it's a draw.
* If the user’s choice wins based on the rules, it prints "You win!".
* Otherwise, it prints "You lose!".
# Detailed Description on how it works
* The random module is imported to allow the computer to randomly choose Rock, Paper, or Scissors.
* They are stored as string variables (rock, paper, scissors).
* The program asks the user to enter 0, 1, or 2, corresponding to Rock, Paper, or Scissors.
* The random.randint(0, 2) function selects a random number (0, 1, or 2), which corresponds to Rock, Paper, or Scissors.
* The winner is determined based on Rock-Paper-Scissors rules.
* The result (win, lose, or draw) is displayed.
* If the input is invalid, an error message is shown.
