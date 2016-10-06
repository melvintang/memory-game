<h1>WDI Project 1: Memory Game</h1>
<p>My 1st project for General Assembly WDI</p>

<h2>Project link:</h2>
https://melvintang.github.io/memory-game/

<h2>User Story:</h2>
To find all the pairs of the same Pokemon creatures in the least no. of clicks and in the shortest time.

<h2>Goals</h2>
1. To use objects and functions effectively in Javascript 
2. To use jquery for DOM manipulation
3. To improve on code readibility
4. To remove bugs (eg. Controlling the number of clicks by the user and the behavior of the cards)
5. To make a basic game which can be modified and enhanced easily

<h2>Logic flow</h2>
1.  Add event listener for button Play!
2.  Add/change properties to Play!, reset, time and clicks.
3.  Start time.
4.  If time exceeds 600s, print "You lost!" and pause the time. 
4.  Add event listener for reset button which resets the game.
5.  Card Boxes appear.
6.  Shuffle the cards.
7.  Assign the cards to html elements: Add attributes.
8.  Add event listener for each boxes. When clicked: for each card: add elements and atrribute class "selected". Count the       number of clicks. 
9.  After clicking on boxes, check for match: if the number of clicks is even: if the 2 selected cards match, remove classes     'selected' and "unmatched" and remove the cards. Then check for a win. Else just remove classes"selected" and remove the     elements.
10. If there is a win, print "You rock" and pause the time.   
   

<h2>Credits</h2>
Prima, Glen and Kai Lin

