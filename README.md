# Pong Game
A simple pong game developed using JavaScript. This was done as an assignment for CSE-5335 course


<h2><a href="https://simple-pong-game.herokuapp.com/pong.html" target="_blank">DEMO</a></h2>


Project Description
You need to write a JavaScript file pong.js, used in the file pong.html, that implements the following actions:

initialize: initialize the game
startGame: starts the game (when you click the mouse)
setSpeed: sets the speed to 0 (slow), 1 (medium), 2 (fast)
resetGame: resets the game
movePaddle: moves the paddle up and down, by folowing the mouse
Please watch the video pong.mp4 for a demo of how your game should look like.
The pong court is 800x500px, the pong ball is 20x20px, and the paddle is 102x14px. When you click on the Start button or left-click on the court, the ball must start from a random place at the left border of the court at a random angle between -π/4 and π/4. The paddle can move up and down on the right border by just moving the mouse (without clicking the mouse). The ball bounces on the left, top, and bottom borders of the court. Everytime you hit the ball with the paddle, you add one strike. If the ball crosses the right border (the dotted line), the game is suspended and the strikes so far becomes your score. You would need to click on the Start button or click on the court to restart with a zero number of strikes. So the goal of this game is to move the paddle to protect the right border by hitting the ball.
