# treasure_hunt-python
'''
print("**** Welcome to Trrasure Island ****")
print('''*************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/TREASURE
*******************************************************************************''')
cross_road = input("you're at a cross road.Where do you want to go? Left or Right: ")
if cross_road == "left":
    wait_or_swim = input("there is a lake ,Do you want to wait for a boat or want to swim:  ")
    if wait_or_swim == "wait":
        color = input("there is a house with 3 doors. red,yello,blue which one you choose: ")
        if color == "red":
            print("it's a room full of fire.game over")
        elif color == "blue":
            print("you enter a room of beasts . game over")
        elif color == "yellow":
            print("you found the treasure! you win!") 
        else:
            print("you choose a door that dosen't exist")
    else:
        print("you got attacked by an angry trout . game over")
else:
    print("you fell into a hole.game over")
