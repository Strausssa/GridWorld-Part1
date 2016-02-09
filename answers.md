# Part 1

## Set 1
1. The bug stays in a constant pattern moving around the grid. 
2. The direction that its head is pointing at is where it moves 
3. The bug rotates if it isn't moving
4. The bug leaves flowers behind
5. Rotates 90 degrees when the bug hits the wall
6. When a bug is going towards a rock, the bug will rotate 45 degrees and checks to see if there is a rock. If not, the bug then rotates another 45 degrees and goes forward toward the direction.  
7. The flower doesn't move
8. The flower changes color when a bug goes over it and turns darker as the bug goes further and further away. 
9. The Rocks can move but only if you use a certain method which is move and also change color
10. There can't be more than one figure in the grid because bugs and flowers can't.

### Exercises   
1. 0 : North
   45: North East  
   90: East  
   135: South East  
   180: South  
   225: South West  
   270: West
   315: North west
   360: North  
2. The moveTo method allows the bug to move in whatever direction but only if it is inside the bounds of the grid.
3.void setColor  
4. The bug is gone