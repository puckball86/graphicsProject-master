Dara Starr G00209787
Game: "Brick breaker"

Index.html
Set up this to just get a ball made and moving on the canvas. 
First made up my canvas and declared all the variable i need for a ball.
Made a drawball function and called it in a draw function.

collision_detect.html
Used the canvas id to change the size of the canvas
Created a ball object giving it all it parameters
In the balldraw funtion i called the variable with "ball." 
I did the collision detection in the draw function
checking if the ball position and direction is greater than the canvas width minus the ball radius OR the position and direction is less than the ball radius.
Same is done on the y position and direction.

adding_paddle.html
Next i added the paddle and started by making a object paddle.
Added variables for controlling the movement. and set them to false.
add  document.addEventListener() for a keydown and keyup.