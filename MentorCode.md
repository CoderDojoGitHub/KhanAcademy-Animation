```js
//This is the code (and teaching notes) for the Khan Academy lesson that mentors can look over. 
// This can be readily pasted into the Khan Academy platform.

// Section 1 – Drawing – Mentor Demo
// Draw point and line

point(200,200);
line(20,30,60,60);
// Ask to play with size and positioning. Ask for a number. How big is the screen?
// Point out to ignore the Oh noes! Until you are done typing.

// Draw shapes
ellipse(200,200,50,50);
rect(300,0,50,50);

//Let kids play with size, position.

// Show stroke color, including noStroke
stroke(0, 72, 255);
strokeWeight(7);
noStroke();

// Show fill
fill(255, 255, 0);
noFill();

// Ask, how would I make the entire screen one color?
// Draw a big rectangle
fill(23, 166, 69);
rect(0,0,400,400);

// Show background
background(0, 13, 153);

// Show overlapping - draw rectangle first, and then fill it. 
//Point to a kid to give me number for color or size or etc.

stroke(0, 255, 183);
strokeWeight(28);
point(200,200);

// Show crazy overlapping with stroke
stroke(255, 0, 0);
ellipse(200,200,150,150);

//Change stroke to fill and see what happens

//Introduce challenge 1
//Link to scaffold
//Hint – work on one shape at a time.
//Hint – which shape should be drawn first?
//Link to goal in the end


 
//Section 2 – Variables

//Remove body and lines. Delete.
//How do we make the eyes bigger?
//Drag the number to show.
//But that’s only the eyes. Now he’s disproportional. How do we make the whole thing bigger?


//Background first
background(131, 191, 219);

//The head
fill(208, 217, 157);
stroke(0, 0, 0);
ellipse(205,124,142,115);

//The eyes
fill(71, 196, 100);
ellipse(175,126,30,30);
ellipse(230,127,30,30);

//Create eye size variable
var eyesize = 40;
//Ask where should we put the eye size?
//Show what happens when you put the code after instead of before.


//Create body size x and body size y
var bodysizeX = 205;
var bodysizeY = 115;
//Insert variable into the right places

//Tie bodysize Y to bodysize X ---- lets say 200/100 or 2/1.
var bodysizeY = bodysizeX/2;
//Show what happens.

//Play with bodysize – ask them to do it.
//Create bodyposX and bodyposY
var bodyposX = 205;
var bodyposY = 124;
//Insert variable into correct places

//How do we make the eyes move with the body?
//Ask the kids to play with variable. Move the entire character!

//Introduce random variable.
var eyesize = random(40,80);
//Ask kids to refresh.
//Ask to randomize everything, press restart each time

//Section 3: Loops and draw loops.
//What if we don’t want to press restart all the time?

//We want the computer to press restart for us
//Two commands
frameRate(10);
//How fast the computer clicks refresh. 1000 = 1000 times a second

var eyesize = random(40,80);
var bodysizeX = random(150,300);
var bodysizeY = bodysizeX/2;
var bodyposX = 205;
var bodyposY = 124;
var eyeposX = bodyposX+205-175;
var eyeposY = bodyposY+124-126;

//What the computer should do on each refresh. This is a loop! 
//What's in the loop? What's outside of the loop?
var draw = function() {
    
//Make sure to put all the variables before the draw
//Nothing will happen until....


    //Background first
background(131, 191, 219);



//The head
fill(202, 214, 133);
stroke(0, 0, 0);
ellipse(bodyposX,bodyposY,bodysizeX,bodysizeY);

//The eyes
fill(71, 196, 100);
ellipse(175,126,eyesize,eyesize);
ellipse(230,127,eyesize,eyesize);

};
```

