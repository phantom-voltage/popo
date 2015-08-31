# popo


###To Do:
1. Screen scrolling, either continuous or one map per screen
2. Random terrain generation?
  * Maybe handmade elements randomly arranged like Spelunky? 
3. Create enemy class
4. Fix clipping into walls 
  * This happens from right or left collision detection saying the player can freely move in that direction, but because the player moves one pixel per update, by the time they move over the feet are not touching the ground and they fall. We could adjust jump height, or change collision detection for when jumping. I have tested these solutions, but none of them "feel" right
  * Maybe make jump height 5 pixels, and then add climbing animation to grab the edge if y through y+4 of the character sprite touches the top of the pixel.
5. ~~Add jumping animation~~
6. Figure out how combat should work.
  * Y's has simple run into enemies combat, which actually goes along with roguelike move to attack.
7. Generalize rain function to handle ALL background sprites. This is rather simple, but I'm going to watch anime now and do other shit. All background sprites should have the same animation, let's say 4. Then just cycle given that sprites starting frame. Maybe define each type's starting frame in the beginning of the code.


###Notes:
1. In my opinion, jump height should be 5 pixels, as this is enough to jump over one square block and will give a sense of restraint. There is also limited screen space, so jump of 7 or 8 allows you to clear much of the screen.


