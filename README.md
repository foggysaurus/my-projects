# my-projects
This is my first c++ project which took me around 5 months to complete. It was written in C++ 20 standard
This is a highly customizable mod for an old game on Quake Engine which includes:
1) An aimbot (automatic aim which predicts trajectories of projectiles);
2) An ESP (2D OpenGL overlay);
3) Many other gameplay-related utility functions

A video demonstration which explains what it is and what it can do in more detail:
https://www.youtube.com/watch?v=tWvYQY4Qscg&feature=youtu.be

This mod works by inserting a .dll via a LoadLibraryA function into every avaiable game process and then reading and writing values in game memory directly.
In order to retrieve necessary memory addresses and in-game functions I used ReClass, IDA Pro, Cheat engine extensively.
2D overlay uses OpenGL for text and image rendering.

If multiple game instances are launched, inactive windows may be controlled by the main instance. 
