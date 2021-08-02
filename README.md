# Guessing a Number Game

1. Player has to enter a positive number. Other than positive number, if the player enters any string or negative number it displays "Please type a number next time." and quits.

2. For generating a random number,  random is imported from the python libraries.

3. Based on the player input number, it generates one random number upto the range of player input number.

Example : input_number = 5,
          random_number = random.randint(input_number)
          
4. Player has to guess that random number. The game will continue until the player guesses the number.

5. If player guess a number which is above the random number, then it displays "You were above the number!".

6. If player guess a number which is below the random number, then it displays "You were below the number!".

7. If the player guesses the correct number, then it displays "You got it!"

At the end , the player can see in how many guesses he/she got the right answer.
