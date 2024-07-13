# OS-SimpleShell

---

# Simple Shell

Simple Shell is a basic UNIX shell implementation written in C programming language. It provides a simple command-line interface for users to execute commands, handle background processesupports piped commands, and maintains a command history. The shell supports standard I/O, memory allocation, string manipulation, process creation, signal handling, and command history.

## Features

- Standard Command execution: Execute single commands entered by the user.
- Piped commands: Support for executing commands with pipes using the | symbol.
- Command history: Maintains a history of executed commands.
- Background execution: Support for running commands in the background using `&` symbol.
- Signal Handling: Gracefully handle signals like Ctrl+C.
- Process Management: Create and manage child processes for command execution.

--- 

## Usage

### Compilation

To compile the shell:
```
gcc -o simple_shell main.c
```

### Running the Shell

Execute the compiled binary to start the shell:

```
./simple_shell
```

### Commands

The Simple Shell supports the following commands:

- Single commands: Enter any single command to execute. (Type any valid shell command and press Enter.)
- Piped commands: Use the pipe operator (`|`) to execute piped commands.
- Background execution: Append `&` at the end of the command to run it in the background.
- `exit`: Terminate the shell. (Type exit to exit the shell.)
- `history`: Display the command history. (Type history to display the list of executed commands.)

---

## Examples

### Single Command Execution

```
$ ls -l
```

### Piped Commands

```
$ ls -l | grep .txt
```

### Background Execution

```
$ sleep 10 &
```

### Command History

To display the command history, enter:

```
$ history
```
---

## Contributions
Under the guidance of [Prof. Vivek Kumar](mailto:vivekk@iiitd.ac.in) at IIIT Delhi.
- [Aryan Jain, 2022111, IIIT Delhi](mailto:aryan22111@iiitd.ac.in)
- [Parth Sandeep Rastogi, 2022352, IIIT Delhi](mailto:parth22352@iiitd.ac.in)
