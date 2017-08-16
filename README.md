# 2D-breakout-game-with-js

This is a simple, 2-dimensional game built in Javascript using the HTML canvas
that operates similar to the classic video game called Breakout. It was built
mostly following the tutorial at [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript).

## Installation and Set Up  
Below are the instructions for installing this application.
*These instructions are valid as of 2017.08.16*

### Environment Set Up  
1. Clone this repository to your local environment.
  1. Fork this Github repo.
    1. In a web browser, visit https://github.com/NFabrizio/2D-breakout-game-with-js
    2. Click the Fork button in the upper right corner of the screen
    3. In the "Where should we fork this repository?" pop up, select your username.
    Github should create a fork of the repo in your account
  2. Clone your fork of the 2D-breakout-game-with-js repo.
    1. In the terminal on your local environment, navigate to the directory where
    you want to clone the 2D-breakout-game-with-js repo  
      `cd ~/path/to/your/directory`
    2. In the terminal, run:  
      `git clone [clone-url-for-your-fork]`  
      The URL should be in the format git@github.com:YourUsername/2D-breakout-game-with-js.git
2. Open the application in a web browser.
  1. Find the index.html file for this repo on your local machine and double click it.
     This should open the file in your default web browser, and the game should
     start automatically.

## Application Use  
This game operates similarly to the classic video game called Breakout. The paddle
can be moved left and right using either the left and right arrow keys or by moving
the mouse left and right on the canvas space. If the ball hits the end of the paddle
opposite to the direction it is traveling (i.e., furthest away), the ball will
bounce with a different trajectory and will speed up. The speed will increase in
steps for each consecutive time it hits the end of the paddle. Forcing the ball
to hit the center of the paddle will cause the ball the return to its normal
trajectory and will step the speed the ball is traveling down one step for each
consecutive time it hits the center of the paddle.  

The goal of the game is to hit and destroy all of the blocks at the top of the
screen by forcing the ball to strike each block.  

At the beginning of the game, the player will be given three lives. Each time the
ball hits the bottom of the game board, play will be re-started and one life will
be deducted from the player's lives. The game ends when either there are no more
blocks left at the top of the screen (i.e., the player wins) or when the player
has no more lives and the ball hits the bottom of the game board (i.e., the player
loses).

To restart game play after the game ends, simply click the "OK" button in the alert
box that appears notifying the user of the game ending.
