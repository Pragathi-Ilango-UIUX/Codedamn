# Concepts used

  **transform: rotate(0deg);** - Rotates an element around a fixed point on the 2D plane (clockwise or counter-clockwise according to a given degree).

  **transform: translate(0px, 1px);** - Shifts an element from its current position (according to the parameters given for the X-axis and the Y-axis).

  **@keyframes rule** - The animation will gradually change from the current style to the new style at certain times (Here, the animation must be bound to an element).
    - By using percent, you can add as many style changes as you like (that dictate how the element transforms over time.)
    - The animation-duration property defines how long an animation should take to complete. If the animation-duration property is not specified, no animation will occur, because the default value is 0s (0 seconds). 

  **animation: transformRotate 1s;** - The transformRotate animation is applied to the respective element. The animation will run for 1 second and then return the animated element to its original state once the animation completes. 
  
  **grid-template-columns: 1fr 1fr 1fr;** - Specifies the number (and the widths) of columns in a grid layout. (fr- fraction)

 *Note*- fr unit is a flexible length unit that represents a fraction of the remaining space in the grid container (designed specifically for CSS grid layouts)

# How to create the wobble effect? 

At each 10% interval (representing each 1/10th of the total animation duration), the box is translated and rotated.

# Reference links 

 * https://www.w3schools.com/css/css3_animations.asp
 * https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scale
 * https://www.w3schools.com/css/css3_2dtransforms.asp
 * https://developer.mozilla.org/en-US/docs/Web/CSS/transform
