# Matching Game

This assessment task requires an interactive game.

When the game starts, five faces are shown on the left and four are shown on the right. This is illustrated below.
![Final](https://github.com/dmsuzuki/MatchingGame/blob/master/picture3.png)
The left and right sides are identical, except for one thing: the left side has one extra face. The user needs to click on that extra face. 
If anything except the correct face is clicked, a message is displayed saying that the game is over. 
If the correct face is clicked, all the currently displayed faces are deleted and a new set of faces is shown at random positions. 
Each time a new set of faces is shown there will be 5 more faces than before, on both the left and the right sides. 
There will always be one extra face shown on the left.

 - [Part 1] - Developing the web page content without JavaScript.
 - [Part 2] - Generating the left side images.
 - [Part 3] - Handling the right side.
 - [Part 4] - Finishing the game.
	
#### Requirements
**Part1:** 

 - The web page, without JavaScript is created.
 - The result will look like this when viewed in a browser. As you can see, only the instructions and the middle line are visible.
![Picture1](https://github.com/dmsuzuki/MatchingGame/blob/master/picture1.png)

**Part2:** 

- For this stage you need to add JavaScript code which generates numberOfFaces images on the left side. (There are no right side faces in part 2).
- The result will look like this when viewed in a browser.
![Picture2](https://github.com/dmsuzuki/MatchingGame/blob/master/picture2.png)

**Part3:** 

- You need to extend the JavaScript code developed in part 2 to handle the right side.
- The DOM will look like this:
![DOM](https://github.com/dmsuzuki/MatchingGame/blob/master/dom.png)

**Part4:** 

- You need to extend the JavaScript code developed in parts 2 and 3, mainly to handle the events and game logic.

----------
**Further Notes:**
>  Submit one single HTML file, which includes the JavaScript code within it. That means there are no links to external JavaScript files or any other files in this assessment task. 