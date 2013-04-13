# Khan Academy Animation

A lesson on variables, loops, if statements using the Khan Academy platform.


## Get set up!

Go to Khan Academy's website:

https://www.khanacademy.org/cs

Click on new program


## Drawing

Watch mentor demo the drawing commands

- Play with lines and shapes
- Play with size and positioning – drag it!

### Code Reference

Note: capitalization matters! Semicolons too!

- Draw a bezier curve

   ```
   bezier(x1, y1, cx1, cy1, cx2, cy2, x2, y2);
   ```

- Draw an ellipse

   ```
   ellipse(x, y, width, height);
   ```

- Draw a line

   ```
   line(x1, y1, x2, y2);
   ```

- Draw a point

   ```
   point(x, y);
   ```

- Draw a rectangle

   ```
   rect(x, y, width, height);
   ```

- Draw a triangle
 
   ```
   triangle(x1, y1, x2, y2, x3, y3);
   ```

- Set the fill color for shapes

   ```
   fill(red, green, blue);
   ```

- Turn off fill for shapes

   ```
   noFill();
   ```

- Set outline color for shapes

   ```
   stroke(red, green, blue);
   ```

- Turn off outlines for shapes

   ```
   noStroke();
   ```

- Change the thickness of outline color

   ```
   strokeWeight(size);
   ```

- Set a background color

   ```
   background(red, green, blue);
   ```

- Store all 3 color components in one variable

   ```
   color(red, green, blue)
   ```

**Play with overlapping of code to make some shapes come in front of each other**


### Challenge #1

Click here http://www.khanacademy.org/cs/drawing-demo-challenge-1-prompt/1541038466

Challenge is to make this look like http://www.khanacademy.org/cs/drawing-demo-challenge-1-solution/1541146483


### Challenge #2

- Make any character with shapes – Face, Eyes, Mouth.
- Requirements – use three different shapes, use three different colors.
- Color background


**Examples**


- http://www.khanacademy.org/cs/winston/823977317
- http://www.khanacademy.org/cs/paul-frank-monkey/1000178956
- http://www.khanacademy.org/cs/silly-pinguin/1156504170

Hint: Use the documentation for help:

http://www.khanacademy.org/cs/docs



## Introduction to Variables

http://www.khanacademy.org/cs/section-2-variables/1541110625

- Names a Variable: var name = number
  - Change the size of eyes.
  - Change size of body
  - Change position


**Challenge**

- Make the entire character move.
- Need to tie all X positions to one variable and all Y positions to one variable.
- http://www.khanacademy.org/cs/section-3-animation-one-direction/1540944644
- Introduce random variable

**Challenge**

- Randomize everything!



**Other resources**

- Practice using variables
- http://sandcastle.khanacademy.org/media/castles/jeresig:cs-exercises/exercises/cs_variables_1.html

Example: http://www.khanacademy.org/cs/winston-coderdojo-part-21/1355580688



## Animation Step 1

- Frame Rate – how fast the computer presses restart: frameRate(10);
- Draw loop

   ```
   var draw = function() { }
   ```

- http://www.khanacademy.org/cs/section-3-animation/1541400394
- Play with putting different variables into the draw loop.
- Play with frameRate

**Challenge**

- Make character move in one direction
- Instead of random number, we want a direction. Which number should we change to make guy go to the left?
- http://www.khanacademy.org/cs/section-3-animation-challenge/1541200948


## Animation Step 2


- Draw a wall somewhere.
- Make character move toward wall.
- If Statements
  - Character change directions when hit wall.
  - https://www.khanacademy.org/cs/section-4-if-statement/1541323643
- Key press
  - Winston change direction if you press a key.
  - keyIsPressed && keyCode === RIGHT
- http://www.khanacademy.org/cs/pong-level-2/1376893644


**Challenges**

- Character stands still. Only move if you press a key.
- Character move up and down as well as left and right.
- Draw a floor and make character bounce left and right.
