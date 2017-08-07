# Hello-world
Hello everybody i am here to learn more about programming and i use linux for my program experience.
All tips and tricks for linux will be appreciate.
I now also the how to code a little game in linux terminal. (Mystery number).
Here the code for more information.

import random
nombre_secret=random.randint(1,100)
essai=1
status="recherche"

while (essai < 11) and (status != "trouvé"):
    print("essai : ",essai)
    tentative = input("Enter a number : ")
    tentative=int(tentative)
    if tentative < nombre_secret:
        print("trop petit")
    if tentative > nombre_secret:
        print("trop grand")
    if tentative == nombre_secret:
        print("Congradulation! You have find in ",essai,"coups.")
        status="trouvé"
    essai = essai + 1

if status != "trouvé":
    print("The secret number was :",nombre_secret)

print("Have a great day.") 
 
 
 You can copy and paste this little program in a text editor and the name has to finish with .py
 ex: Mystery number.py
 ex:The number program.py
 etc...
 
 After, in terminal you gonna write python3 Desktop/Program/You program name.py
