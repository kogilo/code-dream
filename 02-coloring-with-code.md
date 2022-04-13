### Coloring with code
```
// face
ellipse(202, 208, 300, 300);

// eyes
ellipse(157, 151, 40, 40);
ellipse(304, 142, 40, 40);

// mouth
ellipse(257, 240, 120, 136);

```

#### After 

```
background(148, 251, 255); // RGB
noStroke();

// face
fill(255, 255, 0);
ellipse(202, 208, 300, 300);

// eyes
fill(0, 0, 0);
ellipse(157, 151, 40, 40);
ellipse(304, 142, 40, 40);

// mouth
fill(255, 0, 0);
ellipse(257, 240, 120, 136);

// headband
strokeWeight(33);
stroke(250, 0, 242);
line(83, 116, 271, 74);

```


#### Challenge: Sunny snowy day
```
// Background
background(65, 193, 219);


// The ground
fill(0, 255, 111);
rect(0, 300, 400, 100);


// The sun
fill(255, 234, 0);
ellipse(80, 64, 100, 100); 


// The snowman
fill(232, 220, 220);
ellipse(200, 300, 150, 150);
ellipse(200, 200, 100, 100);
ellipse(200, 120, 75, 75);
```