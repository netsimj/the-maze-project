# The Maze Project
![maze gif](https://user-images.githubusercontent.com/88714347/171422634-8adc8811-2559-4ba1-967f-4caf909c3f22.gif)
- The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!.
- The Maze was written was written in C ussing SDL2 library. Deveploment was performed using MacOS - gcc (Apple clang version 14.0.0 (clang-1400.0.29.202)).
- It runs on Mac OS X and Linux/Ubuntu. The game uses the technique raycasting to create the apparent 3D nature of the maze.
# About SDL2
- Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games. For more information on [SDL2](https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer)
`
# Requirements to Play
  - Linux/ubuntu or Macos
  - SDL2 and its sdl_image
# Installation

 - SDL2 installation
```
brew install SDL2

brew install SDL2_image

brew install SDL2_ttf
```
# Play the game
 - Clone the [github repository](https://github.com/Susiniosgit/3D_Maze.git)
 - Compile all .c files in the maze directory:
  ```
  gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm $(sdl2-config --cflags --libs) -lSDL2_image -o maze
  ```
 - Execute ./maze and play the game.
 - Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
 - Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)
# Controls
 W or up arrow key - Moving forward
 S or down arrow - Moving backward
 left arrow key - to rotate the player in counter clock wise direction
 right arrow key - to rotate the player in clock wise direction

# Flow chart
![Capture](https://user-images.githubusercontent.com/88714347/171421868-d6a7a3d6-6acd-495e-9506-7ab381bba5a4.JPG)
# Project Demo
 [![The Maze](https://imgflip.com/gif/7cv3pm)](https://youtu.be/PWPqSSZgChU)
# Authors
- Ephrem Getachew(https://github.com/Ephrem2166)





