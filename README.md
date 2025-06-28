# Number-Guess

from random import randint

mynum = randint(1, 10)

guess = int(input("Enter the number between 1 and 10 "))

if guess == mynum:
   print("Correct!")
else:
   print(f"Wrong! The correct number was {mynum}")
