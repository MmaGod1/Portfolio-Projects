# Raycasting Project with SDL2

# General Information
This project implements a basic 3D raycasting engine using SDL2. It is designed to create a window and render walls using raycasting techniques. As you progress through the different parts of the project, you'll add features like camera orientation and rotation.

# Compilation and Execution
- **System**: The project will be compiled on **Ubuntu 14.04 LTS**.
- **Compiler**: `gcc` (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- **Flags**: The following `gcc` flags will be used:
  - `-Wall`
  - `-Werror`
  - `-Wextra`
  - `-pedantic`

# Project Guidelines
- **Code Organization**: Keep a clear structure in the repository.
  - Store source files in a `src/` directory.
  - Headers should be kept in an `inc/` or `headers/` folder.
- **Code Limitations**:
  - Functions should be a maximum of **40 lines long**.
  - No more than **80 columns** per line.
  - Each file should contain no more than **5 functions**.
  - Comment all functions to explain their purpose.
- **Betty Style**:
  - The code will be checked using **Betty** style guidelines. Ensure all code complies with this style.

# File Management
- Do not push any **object files** (`.o`), **temporary files** (`*~`), or unused source files to the repository.
  
# Part 0: Walls!
- **Objective**: Create a window with SDL2 and use raycasting to draw walls.
- **Requirements**:
  - The camera doesn’t need to rotate during execution, but you must provide a way to modify the camera angle in the code for testing purposes (after recompiling).
  - The color of the walls must be different from the ground/ceiling.
  - No need to parse the map from a file, but you must provide a way to modify the map in your code (e.g., using an array of integers or characters).

# Part 1: Orientation
- **Objective**: Add color differentiation for walls based on their orientation.
- **Requirements**:
  - Walls facing **NORTH** and **SOUTH** should have a different color from those facing **EAST** and **WEST**.

# Part 2: Rotation
- **Objective**: Implement camera rotation during execution.
- **Requirements**:
  - The camera should rotate when the **left/right arrow keys** are pressed, or when the **mouse** is moved (similar to a FPS game).

# Repository Structure
```
|-- inc/
|   |-- [header files]
|
|-- src/
|   |-- [source files]
|
|-- README.md
```

# Usage
To compile and run the project:
```
gcc -Wall -Werror -Wextra -pedantic src/*.c -o raycast -lSDL2
./raycast
```

# Author
- Mmaduchukwu Mmachukwu Godsgoodness

