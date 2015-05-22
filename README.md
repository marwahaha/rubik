# rubik
Rubik's cube simulator and solver, IPython/Jupyter

This was a fun project! The notebook should render on Github, so click on cube.ipynb to play!
Let me know if there are bugs or comments :-)

##Setting up
###Reset
```position = reset_cube()``` will reset the cube to a completed position
###Viewing
```view_cube()``` will visualize the six sides of the cube
###Rotating
```RotateDown(n)``` will rotate the cube down, n times. The full list of rotations is below.
```
RotateDown(n) #rotates cube down
RotateRight(n) #rotates cube right
RotateCC(n) #rotates cube counter-clockwise
```
##Playing with the cube
###Moves
```LU_Move.exec(n)``` will execute the "Left-Up" move, n times. The list of moves is below.
```
LU_Move.exec(n) #Left-Up
MU_Move.exec(n) #Middle-Up
RU_Move.exec(n) #Right-Up
TL_Move.exec(n) #Top-Left
ML_Move.exec(n) #Middle-Left
BL_Move.exec(n) #Bottom-Left
RLU_Move.exec(n) #Right Face, Left-Up (sometimes called Front-Left)
RMU_Move.exec(n) #Right Face, Middle-Up 
RRU_Move.exec(n) #Right Face, Right-Up (sometimes called Back-Left)
```
###Mixing
```mixup(n)``` will make n random moves on the cube, "mixing it up"
###Solving
```solve()``` will (_should!_) solve the cube. This is effectively the algorithm I use when I solve Rubik's cubes.

#Have fun!

