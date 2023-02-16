# SimpleMultiplayerGame
This is assignment #2 for CS532. This project purpose to to practice javascript skills.
For this assignment, you will practice your client-side JavaScript skills by developing a simple game.

First, you must select a simple Multiplayer Game that you will develop a web interface to play. For example, any of the following games would be acceptable:

CheckersLinks to an external site.
Chess Links to an external site.(more complicated than necessary)
Connect 4Links to an external site.
OthelloLinks to an external site.
The linked examples are JavaScript implementations of these games.

As you are implementing a multiplayer game. Implement a simple turn taking mechanism so that two people sitting side-by-side can play the game. You do not have to implement an AI component. Note that single player games are not acceptable. If you are not sure if your game is acceptable please ask the instructor. Note: Tic-Tac-Toe is not acceptable.

The purpose of this assignment is to get you comfortable with using events and JavaScript to manipulate the DOM. Thus your application must:

make use of at least two different types of events excluding "load" (e.g. click & drag)
use JavaScript to change the dom by adding / removing elements
use JavaScript to change text contents of elements on the page
use JavaScript to change the styling of page content either through direct style manipulations or modifying element classes and/or ids
Again, you may not use any kind of existing framework. This game must be programmed exclusively using HTML, CSS, and clientside JavaScript.  All code is to be written from scratch. You may look at other web pages including the examples for ideas about how to implement particular details of your game, but do not copy any code wholesale. You should implement core functionality and style yourself, in your own way. You should acknowledge any sites that you strongly referenced in a readme.txt file in the submission.

You should work to make the game as playable as possible, but focus on implementing at least the basic mechanics. It is highly suggested that you design your game's code such that the state of the game, e.g., where the pieces are on the board, is stored in a JavaScript data structure separate from the DOM. Then have code that updates the DOM based on the contents of the data structure. Interactions with the elements on your page would then update the game state object, and then trigger updating the board. Separating this functionality will significantly reduce the effort required for implementing the next assignment.

Submit a zip file containing all of your code for the assignment. Also submit a link where the game is hosted live on your web.nmsu.edu page.

Bonus 10pts: Implement some kind of animation using Javascript and/or CSS that contributes to the play experience of the game. For example, pieces animating as they move around the board.
