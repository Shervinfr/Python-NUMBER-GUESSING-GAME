Python Number Guessing Game

Welcome to the Python Number Guessing Game! This is a fun and simple program where you try to guess a randomly generated number between a specified range.
🎯 How the Game Works

    The program generates a random number between 1 and 100 (default range).
    You enter your guesses to try to match the generated number.
    The program provides feedback:
        Too low if your guess is less than the number.
        Too high if your guess is greater than the number.
    When you guess the correct number:
        The program congratulates you and displays the total number of guesses.
    Invalid inputs or guesses outside the range will prompt an error message.
    
📝 Code Explanation
Key Components:

    Random Number Generation: The random.randint(lowest_num, highest_num) function generates a random number between lowest_num and highest_num.

    Input Handling:
        Ensures the user inputs a valid number using guess.isdigit().
        Checks if the number is within the specified range.

    Game Loop: The while is_running loop keeps the game running until the user guesses the correct number.

    Have fun guessing the number! 🎉
