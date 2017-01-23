_HCDE 598 Winter 2017_
# Week 1 Homework

## Lego Family
_Due Saturday, 01/28, at 9pm_

### Goals
You will program your very own lego family. You can base it off a TV show (Simpsons is shown below), a movie, a comic, or even your own family if you want. Look [here](https://www.prote.in/journal/articles/imagine-by-lego) for more inspiration. This assignment will also help you practice with functions, variables, declarations and assignment statements. These ideas help make computations dynamic in interesting ways.

### Review
* Sizes are always given width before height
* Colors are given by three numbers called RGB for _red_, _green_, and _blue_ in the range 0 – 255. 
* `noStroke();` will remove the outlines around your shapes
* Positions on the screen are numbered from (0, 0) in the upper left corner and increase to the right and down
* An shape’s color is set with the `fill` and once set, all shapes are filled with that color until a new `fill` command changes the color
* Use Help > Reference if you are having trouble or want to look up a function

#### Variables
A variable holds a value that can change through the program. Variables are important to dynamic programs, because values change all the time. 

* If more than one function needs access to a variable you should declare it at the top of your code (.e.g, `var position = 0;`)
* Declaring and initializing a variable tells p5.js that `position` is a variable that will be used in the program and that `position` starts with the value `0`
* If the variable `position` holds the value `21`, `position = 21;` and then later in the program, we write `position = 23;` then the value of position has changed from what it was (21) to 23

### Specification
* Your Lego Family project should have a background color that is not white
* Ideally your canvas will be around 900 x 600 or larger
* Each character should be made out of rectangles, but feel free to add in more details with other shapes (like Maggie's pacifier—an ellipse)
* At least 3 different fill colors should be used for your family
* Your family needs to consist of a minimum of 3 characters
* Your code must use functions to structure your code
* The use of parameters is optional but encouraged

### Task
1. Decide on the inspiration for your family
	* It can be a TV show, movie, comic book, or even your own family
	* Sketch out your family on paper, color it in, and label all the important points so it is easier to program
	* Note: you will be submitting your sketches, so keep them with you.
2. Program basic family
	Program your family in the center of the screen, making sure each character lines up on the same baseline (reference the Simpson family portrait)
3. Add variables
	* At the top of your code add an x position and y position variable for each family member, then add these variables into your code as shown in class
	* Examples for the Simpson's variables are shown below
	* Run your code, and make sure each character is now starting in a corner.

4. Move your family
	* Program your family to start in the corners and move to the center of the screen
	* If you have 3 characters, pick your 3 corners, if you have 4 characters use all 4 corners, if you have more than 4 characters you can have multiple characters start in a corner
	* You will be adding statements similar to `x = x + 1` or `x = x - 1` to make this movement happen; consider the ball code shown in class

5. Stop your family
	* Finally, you will want to program your family to stop once it has reached the center
	* To do this you will want to use the min or max functions as shown in class, e.g., `x = min(0, x);` or `x = max(0, x);` 

### Submission
Add your Lego family to your Github portfolio and submit a link to this project on canvas.

### Extra Challenge
* Add more custom details to your family
* Add an interesting moving background
* After the family meets in the middle, send them back to the edges, and repeat forever

### Reference
* [Lego Family Inspiration](https://www.prote.in/journal/articles/imagine-by-lego)