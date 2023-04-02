# Trailing-Cursor-Effect-With-Different-Color-
Trailing Cursor Effect With Different Color in HTML CSS JavaScript
This is a JavaScript code that creates a trailing cursor effect on a webpage using HTML and CSS. The effect involves creating an array of Dot objects, where each Dot object represents a particle in the trail. The position of the Dot objects is updated based on the movement of the mouse, and the trail is drawn on the webpage using CSS.

The code starts by creating an array of Dot objects and a mouse object to track the position of the mouse. The Dot object is used to scaffold the particles in the trail, and the prototype method draw() is used to set the position of the object's <div> node. The Dot objects are then created and added to the dots array.

The draw() function is called repeatedly using requestAnimationFrame(), and the position of the Dot objects is updated based on the movement of the mouse. The nextDot variable is used to determine the next Dot object in the array, and the x and y coordinates of the Dot object are updated based on the difference between its position and the position of the next Dot object. The speed of the movement can be adjusted by changing the value of .6.

The animate() function is called to start the animation, and the mouse position is updated using a mousemove event listener. The effect can be customized by changing the number of particles in the trail, the speed of the movement, and the color of the particles using CSS classes.
