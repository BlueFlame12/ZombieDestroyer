<html>

  <head>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/processing.js/1.6.6/processing.js"></script>

    <script type="text/processing" data-processing-target="processing-canvas">

PImage kingdom, lost, you;
float zx1, zx2, zy1, zy2, px1, px2, py1, py2, cc, bX, bY, bW, bH, cY, cX, bR;
int lives, score;

void setup(){
  kingdom = loadImage("background2.jpeg");
  lost = loadImage("lost.jpeg");
  you = loadImage("You.png");
  noStroke();
size(1824, 965);
zx1 = 1920;
zx2 = 150;
zy1 = 150;
zy2 = 150;
px1 = 250;
px2 = 150;
py1 = 220;
py2 = 150;
cc= 0;
bX = px1;
bY = py1;
bW = 50;
bH = 50;
rectMode(CENTER);
lives = 3;
textAlign(CENTER);
cX= bX;
cY= bY;
bR = 20;
score = 0;
}

void draw(){
  boolean shoot = circleRect(bX,bY,bR, zx1,zy1,zx2,zy2);
  if(shoot){
   zx1 = random(1919, 1920);
   zy1 = random(0, 1015);
  }
     bX = bX + 10;
  background(kingdom);
  fill(0);
  textSize(100);
  text(lives, width/24, height/4);
  fill(#315F2F);
  zx1 = zx1 - 15;
  rect(zx1, zy1, zx2, zy2);
  fill(#DFE37C);
  rect(px1, py1, px2, py2);
     fill(#9D9595);
   ellipse(bX, bY, bR * 2, bR * 2);
   
  if(keyPressed){
 if(keyCode == UP){ 
   py1 = py1 - 12;
  }
 if(keyCode == DOWN){
  py1 = py1 + 12;  
 }
  if(key == 'w'){ 
   py1 = py1 - 12;
  }
  if(key == 's'){
   py1 = py1 + 12; 
  }
}
 if(zx1 <= 0){
   zx1 = random(1919, 1920);
   zy1 = random(0, 1015);
   lives = lives - 1;
 }
 if(lives <= 0){
     background(lost);
   fill(250, 0, 0);
   image(you, width/3, height/2);
 }
 fill(0);
 text(score, width/15, height/12);
}

void keyPressed(){
 if(key == ' '){
   bX = px1;
   bY = py1;
 }
}

boolean circleRect(float cx, float cy, float radius, float rx, float ry, float rw, float rh) {

  float testX = cx;
  float testY = cy;

  if (cx < rx){
    testX = rx;

  }
  else if (cx > rx+rw){ 
  testX = rx+rw;
  
  }
  
  if (cy < ry){        
    testY = ry;

  }
  else if (cy > ry+rh){ 
    testY = ry+rh;
  }

  float distX = cx-testX;
  float distY = cy-testY;
  float distance = sqrt( (distX*distX) + (distY*distY) );

  if (distance <= radius) {
    return true;
  }
  return false;
}


   // End of code

   </script>

  </head>

  <body>

    <canvas id="processing-canvas"></canvas>

  </body>

</html>