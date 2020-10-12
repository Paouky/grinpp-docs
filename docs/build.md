
## Linux & Mac

### Prerequisites

* CMake 3.8+
* gcc 7.x.x (Tested on gcc 7.4.0)
* uuid-dev

### Instructions

1. In the terminal, navigate to a location of your choice
1. `git clone https://github.com/GrinPlusPlus/GrinPlusPlus.git`
1. `cd GrinPlusPlus`
1. `mkdir build`
1. `cd build`
1. `cmake ..`
1. `cmake --build .`

## Windows

### Prerequisites

* CMake 3.8+
* Visual Studio 2017+ 64-bit with C++ 2017 Support
* OPTIONAL: Visual C++ Tools for CMake

### Instructions

1. Open "Developer Command Prompt for Visual Studio 2019"
1. Navigate to a location of your choice
1. `git clone https://github.com/GrinPlusPlus/GrinPlusPlus.git`
1. `cd GrinPlusPlus`
1. `mkdir build & cd build`
1. `cmake ..`
1. `cmake --build .`

#### OPTIONAL: With Visual C++ Tools for CMake

1. In the terminal, navigate to a location of your choice
1. `git clone https://github.com/GrinPlusPlus/GrinPlusPlus.git`
1. In Visual Studio, go to File>Open>CMake...
1. Choose CMakeLists.txt from GrinPlusPlus folder
1. Choose x64-Debug or x64-Release from the build configurations drop-down
1. Generate CMake Cache and Build All from the CMake menu

Once your code is built, you can just open GrinNode.exe from your bin folder.
