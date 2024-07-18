# PROGIDY_SD_02
Build a program that generates a random number and challenges the user to guess it. The program should prompt the user to input their guess, compare it to the generated number, and provide feedback if the guess is too high or too Iow. It should continue until the user correctly guesses the number and then display the number of attempts it took to win the game.
Sure! Here's an explanation of the program without the code:

### Including Headers
The program includes necessary headers to enable input and output operations, random number generation, and getting the current time. These are essential for functions like reading user input, generating random numbers, and seeding the random number generator.

### Main Function
The main function serves as the entry point for the program, where the execution begins.

### Seeding the Random Number Generator
The program initializes the random number generator using the current time. This ensures that each time the program runs, it produces a different sequence of random numbers, providing variability to the game.

### Generating a Random Number
A random number between 1 and 100 is generated. This number is the target the user needs to guess.

### Initializing Variables
Two variables are initialized: one to store the user's guess and another to count the number of attempts the user makes.

### User Prompt
The program prompts the user to guess a number between 1 and 100.

### Main Loop
A loop runs continuously until the user guesses the correct number. Within the loop, the program:
- Reads the user's guess.
- Increments the attempt counter.
- Checks if the guess is lower, higher, or equal to the random number.
  - If the guess is lower, it prompts the user to guess higher.
  - If the guess is higher, it prompts the user to guess lower.
  - If the guess is correct, it congratulates the user and displays the number of attempts it took.

### End of Main Function
The program ends successfully after the correct number is guessed, indicating a successful execution.

In summary, the program is a number-guessing game where the user tries to guess a randomly generated number between 1 and 100. The program provides feedback on each guess and counts the number of attempts, congratulating the user upon guessing correctly.
