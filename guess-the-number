import random

def guess_the_number():
    print("Welcome to Guess the Number!")
    print("I'm thinking of a number between 1 and 100.")
    
    # Generate a random number between 1 and 100
    number_to_guess = random.randint(1, 100)
    attempts = 0
    guess = None
    
    # Loop until the player guesses the correct number
    while guess != number_to_guess:
        try:
            # Get player's guess
            guess = int(input("Enter your guess: "))
            attempts += 1
            
            # Check if the guess is too high, too low, or correct
            if guess < number_to_guess:
                print("Too low! Try again.")
            elif guess > number_to_guess:
                print("Too high! Try again.")
            else:
                print(f"Congratulations! You guessed the number in {attempts} attempts!")
        except ValueError:
            print("Please enter a valid number.")
    
# Start the game
guess_the_number()
