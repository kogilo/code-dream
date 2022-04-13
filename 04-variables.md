### Intro to Variables

```

var eyeSize = 33;

noStroke();

// face
fill(255, 255, 0);
ellipse(202, 208, 300, 300);

// eyes
fill(46, 46, 41);
ellipse(157, 151, eyeSize, eyeSize);
ellipse(304, 142, eyeSize, eyeSize);


// mouth
fill(252, 65, 65);
ellipse(257, 240, 120, 136);
```

#### Challenge: Bucktooth Bunny


```

ellipse(150, 70, 60, 120);  // left ear
ellipse(240, 70, 60, 120);  // right ear

ellipse(200, 170, 150, 150);    // face

var eyeSize=30;
fill(0, 0, 0);
ellipse(170, 150, eyeSize, eyeSize);  // left eye
ellipse(230, 150, eyeSize, eyeSize);  // right eye

line(150, 200, 250, 200);   // mouth
var teethHight =20;
noFill();
rect(185, 200, 15, teethHight); // left tooth
rect(200, 200, 15, teethHight); // right tooth

```


#### More on Variables

```
// Winston's handsome features don't need outlines
noStroke();

var eyeSize = 40;

var x = 150;

// face
fill(255, 255, 0);
ellipse(x, 208, 300, 300);

// eyes
fill(46, 46, 41);
ellipse(x - 50, 151, eyeSize, eyeSize);
ellipse(x + 100, 142, eyeSize, eyeSize);

// mouth
fill(252, 65, 65);
ellipse(x + 50, 240, 120, 136)
```


#### Challenge: Funky Frog

- **A mouth!**
- Our frog has no mouth! Use the ellipse function to draw a wide mouth on the frog's face, centering the mouth at the same x and y as the face. Make it big enough to eat a lot of flies!

Draw eyes
The frog already has eyeballs, but no pupils. How will he find the tasty flies if he can't see them?? Draw them using two rectangles, and use the x and y coordinates to position them inside the eyeballs (adding or subtracting as necessary).

Hint: Take a look at the code for the eyeballs and do something similar to position the pupils.

```
var x = 200;
var y = 250;

noStroke();
fill(30, 204, 91); // a nice froggy green!

ellipse(x, y, 200, 100); // face
ellipse(x - 50, y - 50, 40, 40); // left eye socket
ellipse(x + 50, y - 50, 40, 40); // right eye socket

fill(255, 255, 255); // for the whites of the eyes!
ellipse(x - 50, y - 50, 30, 30); // left eyeball
ellipse(x + 50, y - 50, 30, 30); // right eyeball
fill(10, 1, 1);
ellipse(x, y, 100, 70);

rect(x-55, y-55, 10, 10);
rect(x+49, y-50, 10, 10);

```
