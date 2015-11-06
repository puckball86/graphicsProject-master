Dara Starr G00209787
Game: "Brick breaker"

"Index.html"
Set up this to just get a ball made and moving on the canvas. 
First made up my canvas and declared all the variable i need for a ball.
Made a drawball function and called it in a draw function.

"collision_detect.html"
Used the canvas id to change the size of the canvas
Created a ball object giving it all it parameters
In the balldraw funtion i called the variable with "ball." 
I did the collision detection in the draw function
checking if the ball position and direction is greater than the canvas width minus the ball radius OR the position and direction is less than the ball radius.
Same is done on the y position and direction.

"adding_paddle.html"
Next i added the paddle and started by making a object paddle.
Added variables for controlling the movement. and set them to false.
add  document.addEventListener() for a keydown and keyup.
Implemented the events in the draw() function.

"game_over.html"
This is where I added collision detection between the ball and the end of the canvas. And also between the paddle and the ball. I added a alert box to say when you have hit the canvas and a document.location.reload(); to start the game again.

"brick_field.html"
Nest part of the game to accomplish was to make a brick field for the player to try and destroy. I accomplished this by making a object for a single 'brick' and then makina a 2d array of 'bricks'. Then I created a drawBrickField() function to out put the on to the canvas and called it in the draw() function.

"brick_field_collision.html"
Final main step was to detect the collisons between the ball and the newly created brick field.

"score.html"
I just delcalred a var score which i used as a counter in the if gor the collision detection. Made it equal to the rows multiplied by the columns. i added a alert box to tell you that you had won if all bricks were destroyed and a document.location.reload(); to start the game again.

"Finished_Game.html"
Jus used this to change colours and a few small things like the pop up comments.


"GENERAL COMMENTS"
Was finding it hard to get gitbash working on my machine at home so eventually installed the github for desktop. 