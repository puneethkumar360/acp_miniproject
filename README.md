# README

## Project Title

2D Graphics Editor

## Description

This project is a simple 2D Graphics Editor developed in C. It provides a canvas of size 80 × 24 where users can draw different shapes using coordinates. The editor supports drawing lines, rectangles, circles, and triangles using the '*' character.

The canvas is represented using a two-dimensional character array. Initially, the entire canvas is filled with the '_' character. Users can interact with the program through a menu-driven interface.

## Features

* Draw Line
* Draw Rectangle
* Draw Circle
* Draw Triangle
* Display Current Picture
* Exit Program

## Functions Used

### clearPicture()

Initializes the canvas by filling all positions with the '_' character.

### displayPicture()

Displays the current contents of the canvas row by row.

### setPixel(int x, int y)

Draws a single pixel ('*') at the specified coordinates if they are within the canvas boundaries.

### drawLine(int x1, int y1, int x2, int y2)

Draws a line between two points using Bresenham's Line Drawing Algorithm.

### drawRectangle(int x1, int y1, int x2, int y2)

Draws a rectangle by connecting four lines between the specified corners.

### drawCircle(int cx, int cy, int radius)

Draws a circle with the given center and radius.

### drawTriangle(int x1, int y1, int x2, int y2, int x3, int y3)

Draws a triangle by connecting three points using lines.

## Technologies Used

* Programming Language: C
* Compiler: GCC
* Standard Libraries:

  * stdio.h
  * stdlib.h


## Sample Menu

1. Draw Line
2. Draw Rectangle
3. Draw Circle
4. Draw Triangle
5. Display Picture
6. Exit

## Learning Outcomes

* Working with two-dimensional arrays
* Using functions and modular programming
* Implementing graphics algorithms
* Handling user input through menus
* Performing boundary checking
* Understanding coordinate-based drawing

## Conclusion

The 2D Graphics Editor demonstrates basic computer graphics concepts using C programming. It allows users to create simple shapes on a text-based canvas and provides hands-on experience with arrays, functions, and graphical algorithms.
