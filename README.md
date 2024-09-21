# 3-100 TREASSURE HUNT GAME 
print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
opt1 = input('You\'re at a crossroad, where do you want to go? '
                'Type "left" or "right".\n').lower()
if opt1 == "left":
    opt2 = input("You are on a shore \n "
                 "Now choose if you want to wait or swim across the shore"
                 "Type the desired Outcome"
                 "Type WAIT or SWIM: ").lower()
    if opt2 == "wait":
         opt3 = input("You got a boat now you will be taken to the doors\n"
                     "Select which door you want to go through\n"
                     "Red , Blue , Yellow: ").lower()
         if opt3 == "red":
                 print("You are in a room full of fire \n Game over")
         elif opt3 == "blue":
                 print("You are eaten by beasts \n Game Over")
         elif opt3 == "yellow":
                 print("Hurray You found the treasure\n You won $50000")
         else :
                print("invalid option . You die for not obeying orders\n Game over")
    else :
         print("You decided to swim ! \n Sorry Alegators ate you Game over")
else :
    print("You fell into a hole \n Game over")
