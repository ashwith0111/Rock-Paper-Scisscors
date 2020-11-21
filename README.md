# Rock-Paper-Scisscors
import random
hand = ["rock", "paper", "scissors"]
playing = True
if playing is True:
    playerMove = input("Enter Your Move")
    ComputerMove = random.choice(hand)
    if playerMove == ComputerMove:
        print("Tie")
    elif playerMove == "rock" and ComputerMove == "scissors" or playerMove == "paper" and ComputerMove == "rock" or playerMove == "scissors" and ComputerMove == "paper":
        print("Player Won The Game")
    elif ComputerMove == "rock" and playerMove == "scissors" or ComputerMove == "paper" and playerMove == "rock" or ComputerMove == "scissors" and playerMove == "paper":
        print("Computer Won The Game")

    print("Player Choice is ", playerMove)
    print("Computer Choice is ", ComputerMove)
