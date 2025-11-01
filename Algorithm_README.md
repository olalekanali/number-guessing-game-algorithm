# Number Guessing Game Algorithm

## Steps to follow

1. Start 
2. Generate a random number between **1 and 10**, and store it into a variable.  
3. Let a variable guess be set to **0** (or any number not equal to generated random number variable).  
4. Repeat the steps below until the players guess equals random number generated:  
   1. Prompt the user to enter a guess between 1 and 10.  
   2. Read the user’s input and store it in the guess variable.  
   3. If guess < random number generated:  
      - Display "Your guess is too low, Try again."  
   4. Else if guess > random number generated:  
      - Display "Your guess is too high, Try again."  
   5. Else (i.e guess = random number):  
      - Display "Congratulations, You guessed the correct number."  
5. End


- **Project Author:** Ali Aliyu  
- **Project Title:** Number Guessing Game Algorithm
 
---
# REVIEW - Number Guessing Game Algorithm


## Steps to follow

 While the player's guess is not equal to the random number:
   1. Ask the user to enter a number between 1 and 10.
   2. Validate input:
      - If the input is not a number, display "Please enter a valid number."
      - If the number is outside 1–10, display "Please enter a number between 1 and 10."
   3. If the guess < random number: 
      - Display "Too low! Try again."
   4. Else if the guess > random number:
      - Display "Too high! Try again."
   5. Else:
      - Display "Correct! You guessed the number!"


---

- **Project Author:** Ali Aliyu  
- **Project Title:** Number Guessing Game Algorithm  
- **Peer Reviewer:** Salome Gabriel  

---

## Improvement by Peer Reviewer (Pseudocode Enhancement)

### Added Input Validation

This improvement ensures that if the user enters a non-numeric input (like letters or symbols),  
the program won’t crash but instead prompts them to enter a valid number.

### Updated Algorithm (with Input Validation)

