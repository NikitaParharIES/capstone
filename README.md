# CPPND: Capstone Snake Game Example

This is a starter repo for the Capstone project in the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213). The code for this repo was inspired by [this](https://codereview.stackexchange.com/questions/212296/snake-game-in-c-with-sdl) excellent StackOverflow post and set of responses.

<img src="snake_game.gif"/>

The Capstone Project gives you a chance to integrate what you've learned throughout this program. This project will become an important part of your portfolio to share with current and future colleagues and employers.

In this project, you can build your own C++ application or extend this Snake game, following the principles you have learned throughout this Nanodegree Program. This project will demonstrate that you can independently create applications using a wide range of C++ features.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  >Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source. 
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.


## CC Attribution-ShareAlike 4.0 International


Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

New Features Added:
- Allow players to enter their names and save their high scores to a text file. [1]
  input username into terminal 
- add new type of food []


how it meets the Rubric

Loops, Functions, I/O:
1. "The project accepts user input and processes the input.
In addition to controlling the snake, the game can also receive new types of input from the player."
2. "The project uses data structures and immutable variables.
The project uses arrays or vectors and uses constant variables."

Object Oriented Programming::
3. "One or more classes are added to the project with appropriate access specifiers for class members.

Classes are organized with attributes to hold data and methods to perform tasks.
All class data members are explicitly specified as public, protected, or private.
Member data that is subject to an invariant is hidden from the user and accessed via member methods."
4. "Class constructors utilize member initialization lists.

All class members that are set to argument values are initialized through member initialization lists."
5. "Overloaded functions allow the same function to operate on different parameters.

One function is overloaded with different signatures for the same function name."

Memory Management:
6. "The project uses move semantics to move data instead of copying it, where possible.

The project relies on the move semantics, instead of copying the object."
7. "The project uses smart pointers instead of raw pointers.

The project uses at least one smart pointer: unique_ptr, shared_ptr, or weak_ptr."
8. "The project makes use of references in function declarations.

At least two variables are defined as references, or two functions use pass-by-reference in the project code."

Concurrency:
9. "A mutex or lock is used in the project.

A mutex or lock (e.g. std::lock_guard or `std::unique_lock) is used to protect data that is shared across multiple threads in the project code."
10. "A condition variable is used in the project.

A std::condition_variable is used in the project code to synchronize thread execution.

"

