<!DOCTYPE html>
<html>

<h1>Part 1:</h1>
<ol>
<li>No, if the bug is completely surrounded, the bug will not move to a new location.</li>
<li>The bug moves in whichever direction that is not blocked.</li>
<li>It rotates to find an opening, and if there is not an opening the bug will just continuously turn.</li>
<li>The bug leaves a trail of flowers that gradually lose their color if the bug does not move over it.</li>
<li>when the bug hits the edge of the grid, it turns until it finds an opening to move to.</li>
<li>The bug will turn until it finds an opening to move to.</li>
<li>Yes, the flower spins if the bug moves over it.</li>
<li>If the bug moves over it, it resets the color and the flower spins.</li>
<li>No</li>
<li>Yes, the bug can occupy the same space as a flower, but the rock cannot.</li>
</ol>
<h3>Excercises</h3>
<ol>
  <li>0 - North</li>
  <li>45 - North East</li>
  <li>90 - East</li>
  <li>135 - South East</li>
  <li>180 - South</li>
  <li>225 - South West</li>
  <li>270 - West</li>
  <li>315 - North west</li>
  <li>360 - North</li>
</ol>
<ol>
<li>You can move the bug anywhere in the grid, If you try to move it outside of the grid, an error will pop up.</li>
<li>setColor</li>
<li>The bug disappeared</li>
</ol>
<h1>Part 2:</h1>
<ol>
  <li>It tells the bug how long each side of the box should be.</li>
  <li>Tells the bug how many steps to take before turning.</li>
  <li>To tell the bug to turn 90 degrees.</li>
  <li>The BoxBug class extends the Bug class.</li>
  <li>It could be, but the user would set it.</li>
  <li>Yes, If the bug hits an obstacle, the bug will change direction, therefore, if the bug's path is interrupted by anything, the bug's path will change.</li>
  <li>After the bug turns.</li>
</ol>
<h3>Excercises</h3>
<ol>
  <li>Instead of turning 90 degrees, the bug turns 45 degrees, making more of an octogonal shape rather than a circle.</li>
  <li> 5. I would have to create a new boxbug and then name it. then I would have to add it to the world and give it a location on the grid.
</ol>
<h1>Part 3</h1>
<ol>
  <li>loc1.getLocation();</li>
  <li>3, 4</li>
  <li>3, 5</li>
  <li>South East</li>
  <li>It returns the adjacent location based on the direction entered as a parameter.</li>
</ol>
<ol>
  <li>You can use the getEmptyAdjacentLocations, and getOccupiedAdjacentLocations commands in order to count how many empty spaces and how many occupied spaces their are.</li>
  <li>Use the isValid command to see if the location is valid on the grid.</li>
  <li>You can find the implementations in a different location.</li>
  <li>I don't believe so, the array list can be printed as a list, so it is easier to read.</li>
  </ol>
<h1>Part 4</h1>
<ol>
  <li>The Critter class extends Actor</li>
  <li>processActors, moveLocs, getMoveLocations, selectMoveLocation, makeMove</li>
  <li>They can if they need to.</li>
  <li>Check for a rock, check for another critter, check for neighbors</li>
  <li>The critter must get the locations that it can move in. Then it must select a move location. And then the critter must make the move to the next location.</li>
  <li>The critter class is used to set all the basics for the subclasses of critter.</li>
</ol>
<ol>
  <li>The chameleon makes its move differently than a critter.</li>
  <li>It is calling the original make move in the Critter class, therefore it has to specify between themakeMove in ChameleonCritter, and the makeMove in Critter.</li>
  <li>I would add these commands in the makeMove function : Flower flower = new Flower(getColor()); flower.putSelfInGrid(gr, loc))</li>
  <li>It doesn't need to edit any of the actors, and it acts similarly to the Bug actor.</li>
  <li>Actor</li>
  <li>It extends the Actor class.</li>
</ol>
<ol>
  <li>It doesn't need to change anything about it, it processes the actors the same way.</li>
  <li>If an actor is directly in front of, to left of, or to the right of a crab, the crab will eat the other actor.</li>
  <li>The crab can only move left to right or right to left, and it can only scan for other actors in front, on its left, or on its right.</li>
  <li>(4, 4)(2, 4)(3, 5)</li>
  <li>There aren' t a lot, the crab only moves left and right and.</li>
  <li>If there are objects preventing the crab from moving the crab will turn.</li>
  <li>They only check for the other actors, they don't check for eachother.</li>
</ol>
</html>
