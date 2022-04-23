#### Resizing shapes with variable expressions


```
noStroke();

var faceSize = 661;
var mouthSize = 1/2 * faceSize;
var eyeSize = 2/15 * faceSize; // 40/300ths -> 4/30 -> 2/15
// https://www.khanacademy.org/math/arithmetic/fractions

var x = 200;
var y = 200;

// face
fill(255, 255, 0);
ellipse(x, y, faceSize, faceSize);

// eyes
fill(46, 46, 41);
ellipse(x - 1/6 * faceSize, y - 1/6 * faceSize, eyeSize, eyeSize);
ellipse(x + 1/3 * faceSize, y - 1/5 * faceSize, eyeSize, eyeSize);

// mouth
fill(252, 65, 65);
ellipse(x + 1/6 * faceSize, y + 2/15 * faceSize, mouthSize, mouthSize);

```


#### Challenge: Brown bear eyes


```
noStroke();
var x = 160;
var y = 260;
var faceSize = 360;

var eyes = faceSize/8;

// ears
var earSize=faceSize*1/2;
fill(89, 52, 17);
ellipse(x-faceSize*2/5, y-faceSize*2/5, earSize, earSize);
ellipse(x+faceSize*2/5, y-faceSize*2/5, earSize, earSize);

// face
fill(163, 113, 5);
ellipse(x, y, faceSize, faceSize);


//eyes 
fill(0, 0, 0);
ellipse(x-faceSize/4, y-faceSize/8, eyes, eyes);
ellipse(x+faceSize/4, y-faceSize/8, eyes, eyes);


//nose
fill(89, 52, 20);
ellipse(x, y+faceSize/8, faceSize*4/15, faceSize/5);
```