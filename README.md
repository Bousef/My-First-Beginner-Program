import random

User_Input= input("What is your guess between 1-10: ")

Numbers = ["1","2","3","4","5","6","7", "8", "9","10"]

Computer_Input= random.choice(Numbers)

print("Computer Choice: " + Computer_Input)
if User_Input == Computer_Input:
    print("You guessed the number correctly!")
elif User_Input >= Computer_Input:
    print("You guessed wrong try again")
elif User_Input <= Computer_Input:
    print("Lol Still wrong try again")
else:
    print("Not Quite...")
