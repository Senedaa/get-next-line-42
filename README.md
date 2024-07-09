
# 📖 get_next_line

## About the Project

The aim of this project is to code a function that returns a line, read from a file descriptor. This project will help you understand how files are opened, read, and closed in an OS, and how they are interpreted by a programming language for further analysis. Understanding file manipulation is crucial for data management and persistence.

This project consists of coding a function that returns one line at a time from a text file. For more detailed information, look at the subject of this project.

## 🛠️ Usage

### Requirements

- The function is written in C language.
- You will need the `gcc` compiler and some standard C libraries to run the function.

### Instructions

1. **Using it in your code**

To use the function in your code, simply include its header:

```c
#include "get_next_line.h"
```

When compiling your code, add the source files and the required flag:

```sh
get_next_line.c get_next_line_utils.c -D BUFFER_SIZE=<size>
```

## 📋 Testing

You only have to edit the `get_next_line.c` file and uncomment the `main` function and headers inside it. You can edit `test.txt` files to include different text if you wish to test other cases. Then simply run this command (change "xx" with the desired buffer size):

```sh
gcc -Wall -Werror -Wextra -D BUFFER_SIZE=xx get_next_line.c get_next_line_utils.c && ./a.out
```

Or you can also use this third-party tester to fully test the project:

[Tripouille/gnlTester](https://github.com/Tripouille/gnlTester)

---
