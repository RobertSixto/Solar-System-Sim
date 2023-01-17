# Solar-System-Sim
A 2d simulation of some planets, their orbits,  and their moons. Written in JavaScript. This is a modded version of the animation found here: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_animations#result

Changes include:
The addition of a second larger planet with two moons and a wider orbit. 
The addition of planet spin.
Code optimizations for performance. For example, in the original program, a new 'date' object was being created on every pass of the main animation loop. The current build only creates a single date object for use in calculating draw positions. 
Frequently reused code was moved to helper functions.
