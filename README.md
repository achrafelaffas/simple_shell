# Simple Shell Project

This is a basic implementation of a shell in C. The shell provides a command-line interface that allows users to interact with the operating system by executing commands.

## Features

- Execute system commands.
- Change directories using the `cd` command.
- Handle background processes using the `&` symbol.
- Basic error handling and user-friendly prompts.

## Getting Started

### Prerequisites

- GCC (GNU Compiler Collection) installed
- Unix-like operating system (Linux, macOS)

### Compilation

To compile the shell, navigate to the project directory and run the following command:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
