# Dice
## Description-
This Python script simulates the rolling of a six-sided die. It uses the random module to generate a random number between 1 and 6, representing the result of a die roll. The program then displays a graphical representation of the corresponding die face using ASCII characters. The user is prompted to roll again ('y') or exit ('n'). The loop continues until the user chooses to exit.
## Explanation-
    -It imports the random module to generate random numbers.
    -It initializes a variable response with the value "y".
    -It enters a while loop that continues as long as the value of response is "y".
    -Inside the loop, it generates a random integer between 1 and 6 (inclusive) using random.randint(1, 6) and assigns it to the variable no.
    -It then checks the value of no and prints a graphical representation of a die face corresponding to that number.
    -After displaying the die face, it prompts the user to press 'y' to roll again or 'n' to exit.
    -If the user presses 'y', the loop continues with a new random roll; otherwise, if the user presses 'n', the loop exits, and the program ends.
