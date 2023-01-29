# Make Cheat Sheet

## Basic Syntax

- A `makefile` consists of rules, which have the following format:
```
target: dependencies
commands
```
- `target`: The file that is being built
- `dependencies`: The files that the target depends on
- `commands`: The shell commands to build the target

## Special Variables

- `$@`: The name of the target
- `$<`: The first dependency
- `$^`: All dependencies
- `$*`: The stem of a target, defined as the part of a target that matches a wildcard

## Built-in Rules

- `%.o: %.c`: Compile a `.c` file into a `.o` file
- `%.o: %.cpp`: Compile a `.cpp` file into a `.o` file

## Basic Usage

- `make`: Build the default target specified in the makefile
- `make <target>`: Build the specified target
- `make clean`: Clean up build files

## Additional Resources

- [GNU Make Manual](https://www.gnu.org/software/make/manual/make.html)
- [A Simple Makefile Tutorial](https://www.cs.colby.edu/maxwell/courses/tutorials/maketutor/)
