#A01250270 Ilka Eng
import random
for i in range (1):
#I decided to use randint but you could also use random.range but i dont see a great difference
    x = random.randint(1,100)
    print ("Hello! lets play a game! guess what number im thinking. its between 1 to 100")
    z = int(input("which number am i thinking? "))
#With while i create a loop that it will not break until the user guess the number
while z != x:
    if (z > x):
        print ("No, you are wrong. My number is lower")
        z= int(input("Guess again "))
        continue
    elif (z < x):
        print ("No, you are wrong. My number is greater")
        z= int(input("Guess again "))
        continue
print("Yes, you made it. Congratulations")
