# Windows Graphics Application

A feature-rich graphics application built with C++ and Win32 API, implementing various computer graphics algorithms.

## Features

- **Drawing Algorithms**:
  - Lines (DDA, Midpoint, Parametric)
  - Circles (Direct, Polar, Iterative Polar, Midpoint, Modified Midpoint)
  - Ellipses (Direct, Polar, Midpoint)
  
- **Filling Algorithms**:
  - Circle quarters filling (Lines and Circles methods)
  - Flood fill (Recursive and Iterative)

- **Curves**:
  - Hermite curves
  - Bezier curves
  - Cardinal splines

- **Clipping**:
  - Point clipping
  - Line clipping (Cohen-Sutherland)
  - Polygon clipping

- **File Operations**:
  - Save drawings to file
  - Load saved drawings

## Getting Started

### Prerequisites
- Windows OS
- MinGW-w64 or Visual Studio compiler
- Basic C++ development environment

### Building from Source

1. **Using Code::Blocks**:
   ```bash
   # Open the project file (.cbp) and build
Command Line (MinGW):

bash
g++ main.cpp -o graphics_app -lcomdlg32 -lgdi32 -luser32 -lkernel32
Usage
Select a drawing tool from the menu

Choose a color

Click and drag on the canvas to draw

Use right-click to complete polygons/splines

Menu Options
File: Save/Load drawings

Colors: Change drawing color

Background: Change canvas color

Tools: All drawing algorithms

Clipping: Various clipping operations

Code Structure
text
/GraphicsApp
│── main.cpp          # Main application code
│── README.md         # This documentation
│── graphics_app.exe  # Compiled binary (optional)
Key Functions
DrawLineDDA() - Digital Differential Analyzer line algorithm

DrawCircleMidpoint() - Midpoint circle algorithm

ClipPolygon() - Polygon clipping implementation

FloodFillRecursive() - Flood fill using recursion

DrawCardinalSpline() - Cardinal spline implementation

Contributing
Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.

Future Improvements
Add anti-aliasing support

Implement more filling algorithms

Add zoom/pan functionality

Support for layers
