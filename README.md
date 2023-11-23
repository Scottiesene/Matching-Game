# Creating a Random Number Generator Game with Python

## Introduction

In this project, I build a random number generator game using Python. This game will:
* Generate a number between 1 and 100
* Allow a user to guess what the number may be
* Display messages for the user dependent on the guessed number, so the user will know how to get closer to the correct number
* Let the user know when they have correctly guessed the randomly generated number.


## Random Number Generation

The code shown here is allowing a new random number to be generated between 1 and 100 each time it is ran.

![image](https://github.com/Scottiesene/Matching-Game/assets/151565915/0a0f0879-50d2-4fcf-88d9-ae057edad982)

After running the code for a second time we recieve the number 87 as the randomly generated number, and we will enter a number for the user to guess, which in this example is the number 50.

![image](https://github.com/Scottiesene/Matching-Game/assets/151565915/9fce1cfe-9150-4429-9aa3-e21363251ab8)

## Creating Conditional Statements
We will now begin to create code in order to compare these two numbers using a conditional statement. 

This is stating what to print if the user actually guesses the correct number.

![image](https://github.com/Scottiesene/Matching-Game/assets/151565915/2eb2e89e-031b-4f18-aae4-2103f5bffcc0)

We will begin expanding on the code by inputting data to facilitate the generation of responses for guesses that either exceed or fall short of the desired value.
The prompt "YOUR GUESS IS LOW, PLEASE TRY AGAIN" is triggered due to the initial estimation of 50, which contrasts with the generated number of 87.


![image](https://github.com/Scottiesene/Matching-Game/assets/151565915/1dd9960a-c0ed-4cbe-b098-dcde3fa2b401)

## Analyzation of Responses

Displayed below are a number of outputs given that are dependent upon the number guessed. In this instance we have the guessed numbers of 55, 60, 90, 88, 77 and finally 87, which is the correct number.
Numbers lower than 87 output the message, “YOUR GUESS IS LOW, PLEASE TRY AGAIN”, Numbers higher than 87 return the message, “YOUR GUESS IS HIGH, PLEASE TRY AGAIN”. 
The guessed number of 87 returns the message, “YOU ARE RIGHT! GOOD JOB”, just as intended.

![image](https://github.com/Scottiesene/Matching-Game/assets/151565915/d46ca1ea-9017-413d-b24b-56664f3f9403)

We will run this one more time, and this time our random number that is retuned is 94. We will go through the process one more time and observe the results.

![image](https://github.com/Scottiesene/Matching-Game/assets/151565915/fd9b65c0-690d-421c-bbd0-7ee9a5b96245)

The guessed numbers in this instance, are 80, 95, and then the correct number of 94. These guesses allow for testing each branch of the code written. Each number displayed the corresponding result, so we know that it is robust, and running properly.

## Conclusion

This project, centered around creating a Python-based random number guessing game, provided an excellent opportunity to apply foundational Python programming skills. It allowed me to practice user input handling, conditional statements, and random number generation within the scope of a simple, interactive game.

In essence, this endeavor served as a practical exercise that strengthened my understanding of core Python concepts, demonstrating their application in a real-world context.
