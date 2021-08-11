# SnakeGame
An interactive, playable 2D snake game built with vanilla JS, HTML and CSS

Play the Snake Game application [here](https://nathan-mccraw.github.io/SnakeGame/)

![preview](https://user-images.githubusercontent.com/84479635/128907639-eddf6a6b-489a-4b5d-af81-bbc49e93d9ed.JPG)


## Installation

To use the Snake Game application:

1.  Follow this [link](https://nathan-mccraw.github.io/SnakeGame/) to play the game on your browser.

2.  To play the game locally and to obtain the code base for the application, you can either download a zip file of the code and application or you can fork this repository to       make changes and maintain version control.  You can download the code in a zip file by clicking "code" -> download zip from this repository dashboard (see picture below),       extract the files from the zip file and skip to step 6.  If you wish to fork this repository then go to step 3.

![download code](https://user-images.githubusercontent.com/84479635/128907256-a4157cf2-87f9-4f78-819d-b69426356da7.JPG)

3. If you wish, you can fork this repository, which makes a copy of this repository and stores it to your repository (Github account required).

4.  Clone your repository to your local machine using the command line: [Git Clone](https://git-scm.com/docs/git-clone). This allows you to make changes to the snakegame app,       maintain version control, and save those changes to your repository.  Cloning the app directly from this repository will not let you freely push changes to the app.

5.  Navigate to the root directory of the app.  i.e. If you navigated to C:\Users\{YOUR ACCOUNT NAME}\Documents when you ran 'git clone', then there will now be a directory at       C:\Users\{YOUR ACCOUNT NAME}\Documents\Snake Game.  All application files will now be in this folder.

6.  If you only wish to run the application, navigate to C:\Users\{YOUR ACCOUNT NAME}\Snake Game to find index.html. Open this html file with google Chrome to view the               application without viewing the code.

### Summary
This project was a fun build.  I originally did not play to implement the user settings, but as I continued to refactor my code, I saw the opportunity.  I wrote the code in a such a way that allowed the canvas edging and game area edging to be stored as a variable, this allowed me to set that variable from a DOM input, hence allowing basic user input settings. I continued that pattern and applied the same logic, setting the variable from a DOM input for snake size and apple size.  The snake speed user input settings is actually applied to the 'refresh rate', which is the variable name I used to determine how often the canvas should be drawn.  To increase the snake speed, the interval between canvas updates is decreased.  This allowed me to maintain a consistent movement of the snake, as the incrementation of the snake on the canvas for each canvas drawn is the same regardless of speed, hence the speed is actually only applied to how often the canvas is drawn.  As mentioned, this project was buillt using the canvas in JavaScript and as such deals with drawn shapes, the cartesian coordinate system, and collision detection.


#### Author
Nathan McCraw -- Software Developer [LinkedIn](https://www.linkedin.com/in/nathan-mccraw-5291535b/) | [Personal Website](https://www.nathanmccraw.com/)

