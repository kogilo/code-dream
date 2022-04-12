### Drawing circle with `ellipse` function

 ```
ellipse(x, y, w, h);
```
- x: 0 -400
- y: 0 - 400
- w: width
- h: hight
#### Face
```
ellipse(212, 206, 283, 318);
```
#### mouth
```
ellipse(212, 250, 100, 73);
```
### eyes
```
// Right eye

ellipse(150, 150, 30, 30);
// Left eye
ellipse(278, 150, 30, 30);
```


### Step 1: The bottom
- In this challenge, you'll draw a snowman using the ellipse() command.
- Start off by making a circle, for the bottom of the snowman, with an ellipse() command. This should be the first ellipse() command in your program.
- We've suggested some good values for the ellipse() command in the hint code, but you can change those numbers around, as long as the bottom of your snowman is a circle near the bottom of the canvas and it's not too small!

```
ellipse(200,300,150,150);

ellipse(200,205,105,105);

ellipse(200,143,80,80);

```
### Rectangle

```
rect(76, 45, 250, 300) // face
rect(126, 250, 152, 60) // mouth
rect(140, 150, 30, 30) // left eye
rect(240, 150, 30, 30) // right eye
rect(175, 345, 50, 50) // neck

// unibrow
line(140, 129, 270, 129);

```

### Draw the ground
- We've drawn a snowman like you made in the first challenge, and now you're going to draw more shapes using the commands you just learned.
- In this first step, use the rect() command to draw the ground, so that the snowman isn't just floating in air. 
- You should add your rect() command before the ellipse() commands for the snowman, so that the snowman looks like he is in front of the ground.

```
rect(2,315,397, 84);
ellipse(200, 300, 150, 150);
ellipse(200, 200, 100, 100);
ellipse(200, 120, 75, 75);
```


### Make him wave!
- Now you'll make it look like the snowman is waving by adding arms on both sides of his body, using the line() command.
- You will need to add two line() commands, one for each arm. We've given you some suggestions for numbers in the hint code, but you can pick other numbers as long it still looks like arms. You should add your line() commands after the ellipse() commands for the snowman, so that the arms look like they are in front of the snowman.

```
rect(2,315,397, 84);
ellipse(200, 300, 150, 150);
ellipse(200, 200, 100, 100);
ellipse(200, 120, 75, 75);
line(160, 200, 70, 150);
line(240, 200, 340, 150);

```