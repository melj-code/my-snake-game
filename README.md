# snake by meljcode <a href="https://replit.com/@meljcode/my-snake-game?v=1">🐍</a> 

## Background & Motivations
<div>
If you remember the 90's, it's hard to forget this addictive classic. I have always had an interest in game development, but without the technical skills yet, it was great to build a game completely with Python and get a taste. This project also taught me visually about the importance of separating Classes for efficiency of an application running. 
</div>

Completing this took me on a trip down memory lane to pure 90s nostalgia...

<div>
  <a>
  <img src="https://www.zocalopublicsquare.org/wp-content/uploads/2022/02/nostalgia-L.jpg" alt="drawing" width="400" height=360>
  </a>
</div>

## Code Approach

I build this game using turtle which is a pre-installed Python library that enables users to create pictures and shapes by providing them with a virtual canvas. 


### Main App
The **main.py** file contains the code which displays the screen (where you play the game) as well as the game components, which are imported from separate python files. This file is where the game is run.

### Classes:

<div>
  
**snake.py.py** - A Class for the snake's body. The snake is given a starting postion and initial body size. Functions are created to add a segment to the snake's body if it eats the food, reset the starting position if a collision is made, and how to control the snake.
</div>

<div>
  
**food.py** - A Class for the food the snake is trying to get. A function is created to move the target food once the snake has sucessfully eaten it.
  
</div>

<div>
  
**scoreboard.py** - A Class for keeping your score. Fuctions are created to keep score, update the highest score (so you can beat your own score), and reset.
  
  </div>
  
  
  
## How to Play (with my code):

<a href="https://replit.com/@meljcode/my-snake-game?v=1">PLAY</a> 

1. Click on the link above
2. Click on the game to activate.

### Snake Controls:
<div>
⬆️ - Up
  </div>
<div>
⬇️ - Down
  </div>
  
<div>
⬅️ - Left 
  </div>
<div>
➡️ - Right
  </div>
**If the snake is already moving in a direction, selecting it will reset your score to 0!**





