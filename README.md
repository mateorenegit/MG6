# MG6
1.) for loop will finish before the Update() method finishes. So that causes lag because the loop is running per the Update() (each frame) before Update() even runs.
2.) The player will sometimesn pass through the ground or other objects while jumping. The code disables the player's collider box when moving up rather than disablinh the collision with the platform.
