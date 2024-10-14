# GUess the NUmber
import random

target = random.randint (1,100)

while True:
    Userchoice = input("Guess the number or Quit:")

    if (Userchoice == "quit"):
        break
    Userchoice = int(Userchoice)
    if (Userchoice == target):
        print ("conrats you predict the number, it is:", target)
        break
    elif (Userchoice < target):
        print ("your number is small, guess bigger number.")
    else:
        print ("Your guess is bigger, guess a snmall number.")

print("--- game over---")

