# 3D_Pacman
[CS 179N] Senior Design in Computer Graphics / Electronic Games

3D Game developed on Unity and inspired by Pacman set in a haunted house.

Goal of the game is to collect various puzzle pieces that are scattered
around the haunted house while avoiding the patrolling enemy ghosts.
The player has three lives to collect the puzzle pieces. There are also
power-up tokens that a player can collect to increase their speed, gain
the ability to kill the ghosts, and gain an extra life.

## Contribution
I mostly worked on the modeling and animation of the enemy ghosts. I 
decided to have the ghost body move like a cloth to try to make it a 
little more realistic.

## Source Files
ClothMovement.cs - script that goes through keyframes that were exported
in Blender where I animated the ghost.

SwapGhostBody.cs - script where the ghost's bodies are swapped depending
on whether the ghost is patrolling or not. There are two modes (ghost bodies):
chase and patrol mode. In patrol mode, the ghost body is vertical. In
chase mode, the body is slanted forward.

ghostChaseAnimation - blender file that includes the animation of ghost 
in chase mode

![alt tag](https://raw.github.com/yhern006/3D_Pacman/master/path/to/ghost_gif.gif)
