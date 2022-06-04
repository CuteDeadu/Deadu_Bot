# Deadu_Bot

print("Take Rock , Paper or Scissor to play")

abc=input("Enter: ")

import random

a=("rock","paper","scissor")
a2=(random.choice(a))

abc2=(abc.lower())

print(f"Computer took {a2} so",end=" ")

if (abc2=="rock" and a2=="paper"):
	print("U lost!! ")

elif (abc2=="rock" and a2=="scissor"):
	print("U won!!")

elif (abc2=="rock" and a2=="rock"):
	print("Its a draw, play again to win")

elif (abc2=="paper" and a2=="paper"):
	print("Its a draw, play again to win")

elif (abc2=="paper" and a2=="scissor"):
	print("U lost!!")

elif (abc2=="paper" and a2=="rock"):
	print("U won!!")

elif (abc2=="scissor" and a2=="paper"):
	print("U won!!")

elif (abc2=="scissor" and a2=="scissor"):
	print("Its a draw, play again to win")

elif (abc2=="scissor" and a2=="rock"):
	print("U lost!!")
else:
	print("Invalid Answer")
