# Pong - A game from the 70s
## Complexity
This is a simple version of the game Pong implemented in Lua using the [LOVE2D](https://love2d.org/) game engine. This is a course related project and part of a problemset in Harvards CS50s Game Development course.

The challenge was:
* Understanding the distribution code. 
* Implement an AI for the game Pong. 
* Get familiar with the LOVE2D framework. 

## Files
**main.lua** &rarr; 
contains the implementation of three major function in LOVE2D engine: love.load, love.update and love.draw. These set up the game, control the game loop and draw/display the created sprites. The AI feature that was required for the course is implemented in the love.update function.

**paddle.lua** &rarr; 
contains the class for the Paddle. In Lua every class is equvalent to a table.

**push.lua** &rarr;
contains a library written by Ulysse Ramage that helps to resize the window according to screen width/height without losing the resolution of sprites and text.

**ball.lua** &rarr; 
contains the class that defines the ball and implements collison detection.

## How to run
This game uses the [LOVE2D Game Engine](https://love2d.org/). Install LOVE2D and clone into this repository. Drag and drop the repository `PongAI` on LOVE.exe in the LOVE folder in your program files. Alternatively on windows execute following command:
>"C:\Program Files\LOVE\love.exe" "[`PathToPongAI`]"