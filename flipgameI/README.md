###About
You are playing the following Flip Game with your friend: Given a string that contains only these two characters: + and -, you and your friend take turns to flip two consecutive "++" into "--". The game ends when a person can no longer make a move and therefore the other person will be the winner.

Write a function to compute all possible states of the string after one valid move.

For example, given s = "++++", after one move, it may become one of the following states:

[
  "--++",
  "+--+",
  "++--"
]

###Run time
1 ms

##Solution
This is an easy lvl problem, simply use one for loop from index = 0 to index = array.length - 1 to make changes

*Make sure to put the change back to origin in each pass*
