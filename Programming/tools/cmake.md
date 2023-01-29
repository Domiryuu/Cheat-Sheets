# CMake Cheat Sheet

## Basic Syntax

- A `CMakeLists.txt` file consists of commands, which have the following format:
```
cmake_minimum_required(VERSION version)
project(PROJECT_NAME)
add_executable(EXECUTABLE_NAME source_file1 source_file2 ...)
target_link_libraries(EXECUTABLE_NAME library1 library2 ...)
```


## Variables

- `version`: The minimum required version of CMake
- `PROJECT_NAME`: The name of the project
- `EXECUTABLE_NAME`: The name of the executable to be built
- `source_file`: The source files used to build the executable
- `library`: The libraries to be linked to the executable

## Basic Usage

- `cmake .`: Generate build files for the current directory
- `make`: Build the default target specified in the CMakeLists.txt file
- `make <target>`: Build the specified target
- `make clean`: Clean up build files

## Additional Resources

- [CMake Documentation](https://cmake.org/documentation/)
- [A Practical Guide to CMake](https://crascit.com/2015/03/28/practical-cmake-introduction/)
