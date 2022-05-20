# CppND-Route-Planning-Project

Implementation Of A* Search Algorithm using OpenStreetMap.

############################################################################# Cloning

When cloning this project, be sure to use the --recurse-submodules flag. Using HTTPS:
git clone https://github.com/jaroslaw70/Astar-search-algorithm.git


######################################################################################### Dependencies for Running Locally


cmake >= 3.11.3
    All OSes:   https://cmake.org/install/
    
make >= 4.1 (Linux, Mac), 3.81 (Windows)
    Linux: make is installed by default on most Linux distros
    
    Mac: install Xcode command line tools to get make  https://developer.apple.com/xcode/features/
    
    Windows: http://gnuwin32.sourceforge.net/packages/make.htm
    
gcc/g++ >= 7.4.0
    Linux: gcc / g++ is installed by default on most Linux distro
    
    Mac: same instructions as make - install Xcode command line tools
    
    Windows: recommend using MinGW
    

#################################################################################################### Compiling and Running Compiling

To compile the project, first, create a build directory and change to that directory:

    mkdir build && cd build

From within the build directory, then run cmake and make as follows:

    cmake .. && make

############################################################################## Running

The executable will be placed in the build directory. From within build, you can run the project as follows:

    ./OSM_A_star_search

Or to specify a map file:

    ./OSM_A_star_search -f ../<your_osm_file.osm>

######################################################################## Testing

The testing executable is also placed in the build directory. From within build, you can run the unit tests as follows:

    ./test
