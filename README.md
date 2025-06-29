# Guessing_number_game

import random
target = random.randint(1, 100)

while True:
    userchoice = input("Guess the target or Quit(Q) :")
    if(userchoice == "Q"):
        break
    
    userchoice = int(userchoice)
    if(userchoice == target):
        print("Success : Correct Guess")
        break
    elif(userchoice < target):
        print("Your number was too small, Take a bigger guess..")
    else:
        print("Your number was too big, Take a smaller guess..")A simple Python number guessing game where the user tries to guess a randomly generated number between 1 and 100.
