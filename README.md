# rubik
Rubik's cube simulator and solver in Jupyter notebook

1. View the [interactive Binder notebook](https://mybinder.org/v2/gh/marwahaha/rubik/master?filepath=cube.ipynb).
2. The notebook should render on Github: [cube.ipynb](https://github.com/marwahaha/rubik/blob/master/cube.ipynb).
3. Use [nbviewer](http://nbviewer.ipython.org/github/marwahaha/rubik/blob/master/cube.ipynb).

Of course, forks and comments are welcome!

## Setting up
### Reset
```position = reset_cube()``` will reset the cube to a completed position
### Viewing
```view_cube()``` will visualize the six sides of the cube
### Rotating
```RotateDown(n)``` will rotate the cube down, n times. The full list of rotations is below.
```
RotateDown(n) #rotates cube down
RotateRight(n) #rotates cube right
RotateCC(n) #rotates cube counter-clockwise
```
## Playing with the cube
### Moves
```LU_Move.run(n)``` will execute the "Left-Up" move, n times. The list of moves is below.
```
LU_Move.run(n) #Left-Up
MU_Move.run(n) #Middle-Up
RU_Move.run(n) #Right-Up
TL_Move.run(n) #Top-Left
ML_Move.run(n) #Middle-Left
BL_Move.run(n) #Bottom-Left
RLU_Move.run(n) #Right Face, Left-Up (sometimes called Front-Left)
RMU_Move.run(n) #Right Face, Middle-Up 
RRU_Move.run(n) #Right Face, Right-Up (sometimes called Back-Left)
```
### Mixing
```mixup(n)``` will make n random moves on the cube, "mixing it up"
### Solving
```solve()``` will (_should!_) solve the cube, and print the raw number of moves. This is effectively the algorithm I use when I solve Rubik's cubes.

## Have fun!
I sure enjoyed this project. Let me know if there are bugs or comments :-)

