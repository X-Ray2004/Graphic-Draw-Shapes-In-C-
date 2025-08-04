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

