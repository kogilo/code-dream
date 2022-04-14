### Making animations
```

noStroke();

// position of the car
var x = 10;
    
draw = function() {
    
    // all lines of code inside here will be run repeatedly
    background(151, 244, 247);
    
    // draw the car body
    fill(255, 0, 115);
    rect(x, 200, 100, 20);
    rect(x + 15, 178, 70, 40);
    
    // draw the wheels
    fill(77, 66, 66);
    ellipse(x + 25, 221, 24, 24);
    ellipse(x + 75, 221, 24, 24);
    
    x = x + 1;
};
```

#### Challenge: Exploding Sun


```
noStroke();
 // the beautiful blue sky
background(82, 222, 240);

// the starting size for the sun
var sunSize = 30; 

draw = function() {
   
     
     // The sun, a little circle on the horizon
    fill(255, 204, 0);
    ellipse(200, 298, sunSize, sunSize);
    
    // The land, blocking half of the sun
    fill(76, 168, 67);
    rect(0, 300, 400, 100);
    sunSize = sunSize + 1;

};

```


#### Incrementing shortcuts

```

noStroke();

var x = 200;
var y = 350;
var ballWidth = 300;
var ballHeight = 200;

draw = function() {
    background(255, 206, 71);

    fill(191, 0, 255);
    ellipse(x, y, ballWidth, ballHeight);

    x += 1;
    y -= 2;
    ballWidth *= 99/100;
    ballHeight *= 99/100;
};
```

#### A shorter shortcut


```
noStroke();
var eyeSize = 40;
var x = 200;

draw = function() {
    // face
    fill(255, 255, 0);
    ellipse(x, 208, 300, 300);
    
    // eyes
    fill(46, 46, 41);
    ellipse(x - 50, 151, eyeSize, eyeSize);
    ellipse(x + 100, 142, eyeSize, eyeSize);
    
    // mouth
    fill(252, 65, 65);
    ellipse(x + 50, 240, 120, 136);
    
    eyeSize++;
    // Winston++!!
    // Intelligence++!
};

```


#### Challenge: Parting Clouds

```

noStroke();
var leftX = 147;
var rightX = 292;
var sunRadius = 100;

draw = function() {
    background(184, 236, 255);
    
    fill(255, 170, 0);
    ellipse(200, 100, sunRadius, sunRadius);
    
    // clouds 
    fill(255, 255, 255);
    // left cloud
    ellipse(leftX, 150, 126, 97);
    ellipse(leftX+62, 150, 70, 60);
    ellipse(leftX-62, 150, 70, 60);
    
    // right cloud
    ellipse(rightX, 100, 126, 97);
    ellipse(rightX+62, 100, 70, 60);
    ellipse(rightX-62, 100, 70, 60);
    
    leftX-=1;
    rightX+=1;
    sunRadius+=2;
    
  
    
};

```


#### Mouse Interaction


// mouseX and mouseY

strokeWeight(3);
stroke(57, 0, 214);
fill(0, 210, 247);


draw = function() {
    
    
    background(255, 255, 255);
    
    ellipse(mouseY, mouseX, 30, 30);
    
};
