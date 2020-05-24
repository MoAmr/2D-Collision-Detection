# 2D Collision Detection

Imagine a two dimensional game. In a typical two dimensional game,
we have some game objects which move on the screen and may possibly collide or overlap.
And usually, some of these collisions, at least some of them, are relevant to the game
because they give rise to game events. Therefore, the game needs a way to efficiently
detect collisions, especially if it manages many different game objects at once.