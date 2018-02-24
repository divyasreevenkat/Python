
# program to display the word
import time
def des():

    print('it is the himalayas')
    print('it is an ice cream')
    print('it is during december')
    print('it is very whit')

    time.sleep(5)
    print('you are given only given 4 chances to guess the letter')
    time.sleep(6)
    print('enter yor first guess')
    for word in range(5):
        
        word=input()
      
        if word=='cold':
          print('you are right')
          break
        else:
          print('try out once again')
    game()
 

def dess():

    print('i am hard')
    print('i have fibre on me')
    print('my fruit is called as the vegetable')
    print('i also give  something which is similar to drinks')
    print('i also give shade')
    print('enter the guess')
    for letter1 in range(5):
        word=input()
        if word=='coconut tree':
           print('you are right')
           break
        else:
           print('try out once again')
    game()   

def desse():
    print('enter your name to proceed')
    myname=input()
    print('i am  a good girl')
    time.sleep(2)
    print('i am very honest')
    time.sleep(2)
    print('i am the best friend')
    time.sleep(2)
    print('i am the best daughter')
    time.sleep(2)

    
    print(' guess for the name')
    for letter2 in  range(5):
        myname=input()
        if myname=='divya':
            print('you are right')
            break
        else:
            print('try out once again')
    game()       
        

    
def game():            
     print('select a number between 1 and 3')
     option=input()
     if option=='1':
       des()
     elif option=='2':
       dess()
     else:
       desse()
     

print('do you want  to play the game yes or no')
answer=input()
if answer=='yes':
   game()
else:
   print('thank you its ok')
