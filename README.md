🐚 Mini Shell
A simple Unix-like shell written in C, created as a systems programming project. It supports the execution of basic commands and includes essential shell functionalities such as process creation and basic signal handling.

✨ Features
Execution of external commands (e.g., ls, pwd, echo, etc.)

Built-in commands (cd, exit)

Basic command-line parsing

Process management using fork(), execvp(), and wait()

Signal handling for keyboard interrupts (e.g., Ctrl+C)

Minimal error handling

❌ Not (Yet) Supported
Command chaining with separators (;)

Input/output redirection (>, <, >>)

Piping (|)

Environment variable expansion

⚙️ Technologies
Language: C

Compilation: GCC, Makefile

System calls: fork(), execvp(), wait()
