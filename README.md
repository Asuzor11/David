# David
#python program for a guessing game

secret_number=9
guess_count=0
guess_limit=4
while guess_count<guess_limit:
      guess=int(input('guess:'))
      guess_count+=1
      if guess==secret_number:
         print("you won!")
         break
else:
    print ("game over!")
