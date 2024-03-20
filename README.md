import random 

num = [1,2,3,4,5,6,7,8,9,10]

while True:
    print("Choose a number between 1 to 10")
    choice = int(input("--> "))
    comp = random.choice(num)
    if choice >= 1 and choice <= 10:
        if choice == comp:
            print("Congrats! You chose the right number.")
            break
        else:
            print("Sorry but wrong answer, try again.The number was -->",comp)
    else:
        print("Invalid input"
