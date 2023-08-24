# 0x16. C - Simple Shell
## Group project
Project to be done in teams of 2 people (your team: Oussama Amahrouch,(unpaired))

Project will start Aug 9, 2023 4:00 AM, must end by Aug 24, 2023 4:00 AM

Checker will be released at Aug 22, 2023 11:12 PM

An auto review will be launched at the deadline

## Description

This project is a simple UNIX command line interpreter built as part of the ALX Software Engineering Program curriculum.

## Resources

- [Unix shell](https://en.wikipedia.org/wiki/Unix_shell)
- [Thompson shell](https://en.wikipedia.org/wiki/Thompson_shell)
- [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson)

## Tasks

### 0. Betty would be proud
Ensure the code is beautifully written and adheres to the Betty coding style standards.

### 1. Simple shell 0.1
Develop a basic UNIX command line interpreter with the following features:
- Display a prompt and wait for the user to type a command, which always ends with a new line.
- Re-display the prompt after executing a command.
- Accept command lines composed of just one word; programs should not receive any arguments.
- Display an error message if the system cannot find the executable.
- Proper error handling is necessary, including handling the "end of file" condition (Ctrl+D).

### 2. Simple shell 0.2
Building upon the first version, this iteration should:
- Handle command lines with arguments, allowing more interaction and flexibility for the user.

### 3. Simple shell 0.3
Enhance the shell by incorporating the following functionalities:
- Manage the PATH, allowing for command execution without specifying the full path.
- Ensure that the system does not invoke the fork system call if the command doesn't exist.

### 4. Simple shell 0.4
In this iteration, which enhances further from the third version, we aim to:
- Implement the exit built-in command, allowing the user to shut down the shell gracefully.
- No arguments must be handled with the exit command, ensuring straightforward functionality.

### 5. Simple shell 1.0
In this milestone, building upon the previous version, we aim to:
- Implement the env built-in command to allow users to print the current environment variables to the console. Such a feature adds a layer of convenience and functionality, providing insights into the system's state.
