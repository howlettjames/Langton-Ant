# Langton's Ant

### This is an implementation in C++ language with several simulation options of [Langton's Ant](https://en.wikipedia.org/wiki/Langton%27s_ant) two-dimensional universal Turing machine invented by Chris Langton in 1986. Check more documentation of this work [here]().

## Tech Stack
* C++ language.
* [olcConsoleGameEngine](https://github.com/OneLoneCoder/videos).

## Functionality
When running the program the user can select in between different simulation options, these include:

* Console Dimension: This refers to the size in pixels of the console where the simulation will be displayed.

* How close ants should be: This means how conglomerated the ants will be, the greater the number the closer the range.

* Number of ants.

* Queen life steps.

* Soldier life steps.

* Worker life steps.

* Percentage of queens at start.

* Percentage of soldiers at start.

* Percentage of workers at start.

By playing around with all these options one can find interesting behaviours in the colony.
The program also generates a density histogram of the ants over the space.

## Run the program

In order to run the program you need to:
* Download the code.
* Run in a Linux distribution (Ubuntu recommended).
* Having [SDL2](https://www.libsdl.org/download-2.0.php) and C++ installed on your computer.
* Compile with:
```bash
g++ langton.cpp -DUNICODE -I/usr/include/SDL2 -lSDL2 -lpthread -o langton.out
```
* Run:
```bash
./langton.out
```

## Example of a simulation with rule B3/S23

![Running the simulation](https://github.com/howlettjames/Game-Of-Life/blob/master/Test/test.png "Running the simulation")