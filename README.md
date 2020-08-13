# Create basic C++ project with CMAKE and VSCode

Source: [Visual Code CMake Tutorial](https://code.visualstudio.com/docs/cpp/cmake-linux) 


## Prerequisites
* C++ Compiler and debuger: gcc and gdb
* C++ builder: make
All this programs installed with `sudo apt-get instll build-essential gdb`
* Add VS plugins C++ and CMake from Microsoft

## Creating Hello World program
* To open command pallete: `Ctrl+Shift+P`
* Command `cmake:config` to specify compiler
* Command `cmake:quick` to generate base project
* Command `cmake: Select Variant` to select build type between:
- Debug: disables optimizations and includes debug info
- Release: Includes optimizations but no debug info 
- MinSizeRel: Optimizes for size. No debug info.
- RelWithDebinfo: Optimizes for speed and includes debug info.
* Command: `cmake: Build` to build project for selected target
* Use breack points and click on Debug action to control the program flow

## Mode info: 
- [Overview of C++ extension](https://code.visualstudio.com/docs/languages/cpp)
- [CMake Visual Code tool](https://github.com/microsoft/vscode-cmake-tools/blob/develop/docs/README.md)

