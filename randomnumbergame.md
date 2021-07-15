```
import random

number = random.randrange(1,101)

while(1):
  print("Guess the number 1-100")
  guess = int(input())
  if(guess > number):
    print("Too large!")
  elif(guess < number):
    print("Too small!")
  else:
    print("you got it!")
    break
    ```
