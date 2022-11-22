import time
import random

guess = input("Please select a number from 1 to 6: ")
dice = random.randint(1,6)
print ("The dice throws........and its a.. ")
print (dice, "!!!")
if int(guess) == int(dice):
    print ("WOOHOO, YOU WIN!")
else:
    print ("I am sorry, you lost. Click Run to play again!")
    print("your score is ",dice)
