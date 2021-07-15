```
print("Welcome to 1-D tic tac toe")
print('If you get 3 in a row you win!')

nowinner = True
turn = 0

gameboard = list("."*9)
print(gameboard)

player = 'X'
while(turn < 9 and nowinner==True):
  print("Choose the position on the board (0-8):")
  position = int(input())
  gameboard[position]=player
  
  print(gameboard)
  
  starts = [0,1,2,3,4,5,6]
  
  for s in starts:
    if((gameboard[s]=='X' or gameboard[s]=='O') and gameboard[s]==gameboard[s+1] and gameboard[s]==gameboard[s+2]):
      print("player "+player+" won!")
      turn=9
  
  if(player=='X'):
    player = 'O'
    print("It is now player Os turn")
  else:
    player = 'X'
    print("It is now player Xs turn")
    
    ```
