# Name:void merryChristmas

## Examples:
void merryChristmas() {
  background(0);
  fill(255, 0, 0);
  textSize(50);
  text("Merry Christmas!", mouseX, mouseY);
  if (mouseX>width/2-100) {
    return;
  }
  fill(0, 255, 0);
  text("Feliz Navidad!", mouseX, mouseY+100);

## Description:
the mouse will control where the user sees both Merry Christmas and Feliz Navidad
on the screen. however, when the mouse's X position is greater than half the width of the
screen, then the "Feliz Navidad" goes away. 

## Syntax:
void datatype(){
	background(int, int);
	fill(r,g,b);
	textSize(int);
	text("text", x,y);
	if(something){
		return();
}

fill(r,g,b);
text("text", x,y);
}

##Parameters: 
Name and describe parameters here
none

##Returns:it gets rid of the "Feliz Navidad" after the mouse's X location
is greater than half the width 
no numerical data is returned

##Other notes:
Anything else?
