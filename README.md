# Rapid Unix Shell

## Project Overview
The **Rapid Unix Shell** is a custom Unix-based shell developed in C, designed to execute standard Unix commands like `ls`, `grep`, `mkdir`, and `awk`. It supports parallel command execution, output redirection, and robust error handling. The shell also provides built-in commands like `cd`, `path`, and `exit` for convenient navigation and process control.

## Features
- **Command Execution**: Supports Unix commands such as `cat`, `grep`, `touch`, `mkdir`, and more.
- **Parallel Execution**: Use `&` to run multiple commands in parallel.
- **Input/Output Redirection**: Redirect output to a file using the `>` operator.
- **Built-in Commands**:
  - `cd`: Change directories.
  - `path`: Manage executable search paths.
  - `exit`: Exit the shell.
- **Robust Error Handling**: Includes mechanisms for handling incorrect commands and system call failures.

## Getting Started

### Prerequisites
- A Unix-based environment (Linux or macOS).
- GCC compiler (version 11.4.0 or later).

### Compilation
To compile the project, use the provided `Makefile`. Simply run:
```bash
make
