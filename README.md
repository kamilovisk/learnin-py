# learnin-py
print("''''''''''' SORTING HAT ''''''''''")
print("Answer this questions and see whats house you will be!!!")
print("       🐍🦅🦡🦁          ")

Gryffindor=0 
Ravenclaw=0
Hufflepuff=0
Slytherin=0
# first question
print("Q1- Do you like dawn or dusk?")
print('  1) Dawn')
print('  2) Dusk')
answer= int(input('❔:'))
if answer==1:
 Gryffindor +=2
 Ravenclaw +=2
elif answer==2: 
 Hufflepuff +=1  
 Slytherin +=1
else:
  print(" Answer the question whith 1 or 2 !")
# question 2
print("Q2-When I'm dead, I want people remember as:")
print(' 1) The good')
print(' 2) The creative')
print(' 3) The wise')
print(' 4) The bold')
answer= int(input('❔:'))
if answer==1:
  Hufflepuff +=2
elif answer==2:
 Slytherin +=3
elif answer==3:
 Ravenclaw +=2
elif answer==4:
 Gryffindor +=3
else:
  print("Wrong ")
# question 3
print("Q3-Which kind of instrument most pleases your ear?")
print('1)The violin')
print('2)The trumpet')
print('3)The piano')
print('4)The drum')
answer=int(input("❔:"))
if answer==1:
 Slytherin +=4
elif answer==2:
 Hufflepuff +=4
elif answer==3:
 Ravenclaw +=3
elif answer ==4:
 Gryffindor +=3
  # final if

print("Your house is...")
if Gryffindor > Ravenclaw and Gryffindor > Hufflepuff and Gryffindor > Slytherin:
    print('🦁 Gryffindor!')
elif Ravenclaw > Hufflepuff and Ravenclaw > Slytherin:
    print('🦅 Ravenclaw!')
elif Hufflepuff > Slytherin:
    print('🦡 Hufflepuff!')
else:
    print('🐍 Slytherin!')
   
