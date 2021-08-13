# CPPND: Route Planning Project

## Learnings
This project had been part of the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213) I completed. I had been developing a Open Street Map Planner under expert guidance which got me to learn about and gain practical experience in:
* C++ Foundations (Syntax, Basic types, Control structures 
* AStar Search Algorithm
* Writing Multifile Programs (.h & .cpp files)
* Cmake & Make

## Description

<img src="map.png" width="600" height="450" />

A AStar Search based route planner on a given open street map.  

## Dependencies for Running Locally
* cmake >= 3.11.3
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 7.4.0
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same instructions as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* IO2D
  * Installation instructions for all operating systems can be found [here](https://github.com/cpp-io2d/P0267_RefImpl/blob/master/BUILDING.md)
  * This library must be built in a place where CMake `find_package` will be able to find it

## Basic Build Instructions

1. Clone this repo.
(2. Make a build directory in the top level directory: `mkdir build && cd build`)
3. Compile: `cmake .. && make`
4. Run it: `./traffic_simulation`.
./OSM_A_star_search

To specify a map file: ./OSM_A_star_search -f ../<your_osm_file.osm>

## Testing

The testing executable is also placed in the `build` directory. From within `build`, you can run the unit tests as follows:
```
./test
```

