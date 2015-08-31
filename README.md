# popo


###To Do:
1. Screen scrolling, either continuous or one map per screen
2. Random terrain generation?
  * Maybe handmade elements randomly arranged like Spelunky? 
3. Create enemy class
4. Fix clipping into walls 
  * This happens from right or left collision detection saying the player can freely move in that direction, but because the player moves one pixel per update, by the time they move over the feet are not touching the ground and they fall. We could adjust jump height, or change collision detection for when jumping. I have tested these solutions, but none of them "feel" right
  * Maybe make jump height 5 pixels, and then add climbing animation to grab the edge if y through y+4 of the character sprite touches the top of the pixel.
5. Add jumping animation

