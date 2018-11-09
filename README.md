# 15112-FinalProject-smart-2048-game

my project is based on the famous game 2048. If you do not know it, you can check it on this link ( https://play2048.co/ ). The used language for this project is ( python 2 ).



* game description :
  (‬The game's objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.
    However, one can continue to play the game after reaching the goal)
 
 
 
* The user experience and the features  :
  when the user runs my code he or she will see the following :
  1 - a window that asks the player to choose the game mood either ( one player ) or ( VS The Computer ).
 
    if the player chooses the ( one player ) mood:
    
           . the player will see a window that contains 16 squares (4 x 4) with 2 squares that contain ( 2 and 2 ) or ( 2 and 4 ).
           # you will know more if you try the game form the link.

          . above the 16 squares, the player will see a bar that contains the number of moves.
          # the player can make the moves by using the arrows in the keyboard
          #it will start with 0 and each time the player makes a move that number will increase by 1 

          . the player will keep playing until there is no more allowed moves the player can make .Then the player will see a window
            that asks the player to play again or exit the game.
            if the player chooses to play again he will start from the main window. 
            if the player chooses to exit the game will end.

    if the player chooses the ( Vs computer ) mood:
    
          . the player will see a window that asks the player to choose the difficulty of the game (normal, hard ).
          # you can know more about the AI that my game will include in the AI section down below.
          
          . the player will see two squares, each square will contains 16 squares (4 x4 ).
          # one of the squares will be the player's square and another one will be the computer's square.
          
          . each square will contain the features that the ( one player ) mood has.
          
          . the player should start to make the first move on, then the computer will make the next move. 
          
          . the game will continue like that until there is no more allowed moves the player can make .Then the player will see a window
            that asks the player to play again or exit the game.
            if the player chooses to play again he will start from the main window. 
            if the player chooses to exit the game will end.
            
            
            
 * the AI  
   in the ( Vs computer ) mood I will include AI to teach the computer how to play the game.
   the difficulty will depend on the algorithm that I will use.

   - the normal mood:
   the moves will be based on the ( alpha-beta ) algorithm, which basically makes the computer make certain moves ahead and choose 
   the  choice that leads to the best results

   - the hard mood:
   just like the medium mood but with a bigger number of moves the computer can see. 

* the libraries
# I might include more libraries or change all of them, but these are the libraries that I will use until now 
- Tkinter
- random


* checkpoints:
Duo the first checkpoint ( November 25 ) :
 1 - i will finish the ( one player ) mood
 2 - finish the set of the ( Vs computer ) mood without the AI
 
Duo the second checkpoint ( Dec 6 ):
 - i will finish the AI 
 _ the game will be ready for using 
 
 
thanks for your time

