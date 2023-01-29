# GDB Cheat Sheet

## Basic Commands

- `gdb <program>`: Start debugging a program
- `run`: Start the program being debugged
- `break <line-number>`: Set a breakpoint at the specified line number
- `break <function-name>`: Set a breakpoint at the beginning of the specified function
- `continue`: Continue executing the program until a breakpoint is reached
- `next`: Step to the next line of the program (do not enter functions)
- `step`: Step to the next line of the program (enter functions)
- `finish`: Continue executing the program until the current function returns
- `backtrace`: Display the call stack
- `list`: Display the source code around the current line

## Examining Data

- `print <expression>`: Evaluate and display an expression
- `display <expression>`: Automatically display the value of an expression after each step
- `undisplay <number>`: Stop displaying the value of an expression

## Modifying Data

- `set <variable>=<value>`: Set the value of a variable

## Quitting GDB

- `quit`: Quit GDB
- `exit`: Quit GDB

## Additional Resources

- [GDB Documentation](https://www.gnu.org/software/gdb/documentation/)
- [GDB Tutorial](https://www.tutorialspoint.com/gnu_debugger/index.htm)
