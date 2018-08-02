# #100DaysOfCode Log - Round 1 - andymac (pilotInPyjamas)

The log of my #100DaysOfCode challenge. Started on [July 17, Monday, 2017].

## Log

### R1D1 
Something abstract: Another chapter of "Category Theory For Programmers" and coq "Software Foundations". Looking to write verifiable code.

### R1D2
Something Concrete: Implemented a (fairly naive) algorithm for vector voronoi diagrams in Godot: this will hopefully end with procedural map generation for a simple FPS idea I have.

![Image of a coloured voronoi diagram](./img/Voronoi2.png)

### R1D3
Implemented Bridson's algorithm. This algorithm generates fairly evenly spaced points, so the voronoi polygons are now far more regular than before.:

![Image of a coloured voronoi diagram](./img/Bridsons.png)

#### R1D4 

Generic vectors in C: One of C's limitations is no type safe generic functions. You either use void* or macros. Macros end up inlined everywhere and void* is a bit unsafe. I have a solution that solves both problems:

[Link](https://t.co/CNVp9e589S)

#### R1D5

I used Godot's surface tool to generate the voronoi diagrams as a 3D mesh. Next step is to generate a maze from them and add textures.

![Image of a 3D voronoi diagram](./img/Voronoi3d.png)

#### R1D6

Day 6 #100DaysOfCode : Something simple. Using the Surface tool in Godot to draw procedural meshes. Also learning a bit more Coq and Category theory for something completely different.

![Image of a 3D voronoi diagram](./img/SurfaceTool.png)
