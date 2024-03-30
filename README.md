# Geometric Shapes Library

## Introduction
This C++ library provides functionality for working with various geometric shapes, including Circle, Ellipse, Line, Rectangle, Square, and Triangle. Each shape is represented by a class that inherits from the abstract base class Shape.

## Project Structure

### Headers (Folder)
- **Shape.h**: The Shape header file guards against multiple inclusion using preprocessor directives. The Shape class is declared with a pure virtual function plot(void *ptr), making it an abstract class. This function lacks an implementation in the base class, indicating that derived classes must provide their own implementations.
- **Circle.h**: The Circle class defines a Circle inheriting from the Shape base class. It encapsulates a circle's properties, including the radius (mRadius). The class provides various constructors, a copy assignment operator, and a destructor. Public member functions include methods to calculate the circle's area and circumference, as well as a function plot. However, the actual implementation details of these functions are not provided in the given code snippet.

### Lib (Folder)
The generated library is placed in this lib folder.

### Output (Folder)
This folder contains the final .exe file, which is to be executed to see the final output of the code.

### Src (Folder)
- **Circle.cpp**: The Circle class implementation represents circles and includes functionality for calculating the area and circumference of a circle. It also implements a plot function that generates a GNU Plot script for visualizing the circle and executes it using Gnuplot. The class uses a struct Node to store the radius of the circle, and the implementation ensures proper handling of memory and resource management.

### Test (Folder)
This folder contains the .cpp file which is to be executed for the final output. This file likely includes test cases for the implemented classes.

Feel free to explore each folder and file for detailed implementations and usage of the geometric shapes library.
