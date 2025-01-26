# A* Algorithm with SFML

This project implements the A* pathfinding algorithm using **SFML** for visualization. Follow the instructions below to set up, build, and run the project.

## Tiles:
- **Blue** = Start
- **Red** = Goal
- **Black** = Obstacle

### Interactions:
- To generate obstacles, hold down the middle mouse button.
- Left-click to reposition the start position.
- Right-click to reposition the goal position.
- Press **r** to reset the grid.
- Press **Enter** to run the visualization.

## Prerequisites

### 2. Install SFML

### 1. Install a C++ Compiler
Ensure you have a working installation of `g++`.

#### Windows:
1. Download the SFML library from the [official website](https://www.sfml-dev.org/download/sfml/3.0.0/).
2. Choose the version that matches your compiler.
3. Extract the downloaded files to a directory, e.g., `C:/Users/<YourUsername>/SFML/`.

#### Linux:
1. Install SFML via your package manager:
   ```bash
   sudo apt-get install libsfml-dev

### Ensure the paths to the SFML include and lib directories are correctly specified in the Makefile:
For example:
    INCLUDE_DIR = C:/Users/<YourUsername>/SFML/include
    LIB_DIR = C:/Users/<YourUsername>/SFML/lib

### Run the Following Command to Compile and Link the Project:
make

### To remove the generated object files and executable, run:
Make clean

### After building, run the executable from the terminal or command prompt:
a_star