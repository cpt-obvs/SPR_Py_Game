import random

#Here are the counts/scores for the user and computer. You must have them out of the loop in order for them to total through each loop.
count_user = (0)
count_computer = (0)

#Here we are defining the variables for the amount of times the user picks one of the options (scissors, paper, rock)
count_scissors = (0)
count_paper = (0)
count_rock =(0)

#This is the loop where the game actually lays.
while count_user != 5:
    user_action = input("Pick your poison (Scissors, Paper, Rock): \n")
    possible_actions = ["Scissors", "Paper", "Rock"]
    computer_action = random.choice(possible_actions)
    
    #Here if the user has less than 3 points it'll be a fair game.
    if count_user <=3:
        if user_action == computer_action:
            print("It's a Fucking Tie. Can Someone Actually Win Please?\n")
            if user_action == "Scissors":
                count_scissors = count_scissors +1
            if user_action == "Paper":
                count_paper = count_paper +1
            if user_action == "Rock":
                count_rock = count_rock +1        
        elif user_action == "Scissors":
            if computer_action == "Rock":
                print("The Rock Destroys Your Scissors, Get Good.\n")
                count_computer = count_computer +1
                count_scissors = count_scissors +1
            else:
                print("Congrats....You Cut Some Paper With Scissors...I'm Suuuuuuper Impressed....NOT!\n")  
                count_user = count_user +1
                count_scissors = count_scissors +1
        elif user_action == "Paper":
            if computer_action == "Scissors":
                print("Ha! My Scissors Cut Your Stupid Paper. What Are You Going To Do About It You Wimp.\n")
                count_computer = count_computer +1
                count_paper = count_paper +1
            else:
                print("Your Nerdy Ass Paper May Have Beaten Me, But You're Still A Nerd.\n") 
                count_user = count_user +1
                count_paper = count_paper +1
        elif user_action == "Rock":
            if computer_action == "Paper":
                print("Did You Really Just Let Some Fucking Paper Cover Your Dumb Ass Rock? I Feel Bad For You.\n") 
                count_computer = count_computer +1
                count_rock = count_rock +1
            else: 
                print("Dwayne The Rock Johnson May Have Broken My Scissors, But At Least I'm Not Ugly Like You.\n") 
                count_user = count_user +1 
                count_rock = count_rock +1

    #Here if the user has 4 points, the computer goes into winning mode and will only win the rest of the games.    
    if count_user >= 4:
        if user_action == "Scissors":
            computer_action == "Rock"
            print("The Rock Destroys Your Scissors, Get Good.\n")
            count_computer = count_computer +1
            count_scissors = count_scissors +1
        elif user_action == "Paper":
            computer_action == "Scissors"
            print("Ha! My Scissors Cut Your Stupid Paper. What Are You Going To Do About It You Wimp.\n")
            count_computer = count_computer +1
            count_paper = count_paper +1
        elif user_action == "Rock":
            computer_action == "Paper"
            print("Did You Really Just Let Some Fucking Paper Cover Your Dumb Ass Rock? I Feel Bad For You.\n") 
            count_computer = count_computer +1
            count_rock = count_rock +1

    #Ending of the loop/reset the loop via user input.
    #Also where the game ends one the computer reaches 5 points.
    if count_computer == 5:
        print("I WIN! Wow You Really Suck At This! You Probably Just Suck At Everything. Why Do You Even Bother?\n")
        quit()
    else:  
        print(f"Your Score: {count_user} \n")
        print(f"My Score: {count_computer}")
        print(f"Times you've selected\nScissors: {count_scissors}\nPaper: {count_paper}\nRock: {count_rock}\n")
        next_round = input("Ready To Lose Again? (y/n): \n")
        if next_round.lower() != "y":
            break
        
