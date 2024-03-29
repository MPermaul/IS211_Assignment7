# IS211_Assignment7
Week 7 Assignment 7

Pig is a jeopardy game where you risk everything to see if you can accumulate more points.
The numbers on the die, with exception to \"1\", represent points that can be accumulated by a player.
The winner is the first player to reach 100 or more points.

Game Rules:
  1) A player will roll a die repeatedly. Each number on the die, except the "1", will accumulate points.
      ex:
        The die is rolled and lands on a 3:
            The points accumulated is 3.
        The next roll of the die lands on a 4:
            The points accumulateds is 7 (3 from before, and now 4 from this roll)
            
   2) If a player rolls a "1", all points accumulated in that turn is forfeited, and the next player goes.
      ex:
        If the accumulated points is 7, rolling a "1" will erased these points and the next player goes.
        
   3) A player can keep rolling the die, accumulating points until they decide to hold. Holding will add the accumulated points to
      the players total score. 
    
   4) The first player to with 100 or more points wins the game.


Application Details:

1) This version of PIG allows for a command line parameter using "--numPlayers" to enter in 2 or more players. Anything less than 2 players will not allow the game to continue.

2) When a player has won, a prompt will be provided to start a new game with the same amount of players.

3) A running scoreboard will be displayed at the start of each turn. The scoreboard will display:
  a) the current players score
  b) potential score if they choose to hold
  c) the current highest score
  d) each players score
