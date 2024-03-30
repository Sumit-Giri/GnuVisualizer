# GNU Visualizer

## Introduction
GNU Visualizer is a C++ project aimed at visualizing various geometric shapes using GNU Plot. The project allows users to input coordinates of different shapes and generates visualizations using GNU Plot.

## Features
- Input coordinates for different geometric shapes.
- Visualize shapes using GNU Plot.
- Supports various shapes including Circle, Ellipse, Line, Rectangle, Square, and Triangle.
- Customizable visualization options.


## Usage
1. Run the executable.
2. Follow the on-screen prompts to input coordinates for different shapes.
3. Once coordinates are input, the program will generate a visualization using GNU Plot.

## Project Structure
- **headers/**:
- **Shape.h**: The base class header file with pure virtual functions for plotting shapes.
- **Circle.h**: Header file for the Circle class.
- **Ellipse.h**: Header file for the Ellipse class.
- **Line.h**: Header file for the Line class.
- **Rectangle.h**: Header file for the Rectangle class.
- **Square.h**: Header file for the Square class.
- **Triangle.h**: Header file for the Triangle class.

- **src/**:
- **main.cpp**: Contains the main logic for inputting coordinates and generating visualizations.
- **Circle.cpp**: Defines the Circle class and implements functionality for plotting circles.
- **Ellipse.cpp**: Defines the Ellipse class and implements functionality for plotting ellipses.
- **Line.cpp**: Defines the Line class and implements functionality for plotting lines.
- **Rectangle.cpp**: Defines the Rectangle class and implements functionality for plotting rectangles.
- **Square.cpp**: Defines the Square class and implements functionality for plotting squares.
- **Triangle.cpp**: Defines the Triangle class and implements functionality for plotting triangles.
- **Output/**: Contains the generated visualizations.

## Dependencies
- GNU Plot: Ensure GNU Plot is installed on your system to generate visualizations.

## Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The project was inspired by the need for a simple visualization tool for geometric shapes.
- Special thanks to GNU Plot for providing powerful visualization capabilities.

