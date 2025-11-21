# Basic Forks and C Style Development

## Description
This repository contains the source code and answers for Assignment 2 (Lab 5). The project focuses on Process Management in Linux. It includes C programs that demonstrate how to create processes using `fork()`, how to link multiple source files, and how to inspect dynamic libraries using the loader.

## Installation
To compile and run these examples, you need a Linux environment with `gcc` and `make` installed.
If you don't have them, run:
```bash
sudo apt update
sudo apt install gcc make
```
## Usage
I have included a Makefile to automate the compilation of all exercises.

1. Compiling the Code
To compile all three programs (process_creation, output_program, and simple_program) at once, run:
```bash
make
```

2. Running the Examples

2.1. Process Creation (Fork) This program creates a child process and prints the PID of both parent and child.

```bash
./process_creation
```

2.2. The Linker This executable combines file1.c and file2.c to demonstrate separate compilation.
```bash
./output_program
```

2.3. The Loader This is a simple program used to inspect dynamic libraries.

```bash
./simple_program
ldd simple_program
```

## 3. Project Structure
process_creation.c: Code for the fork() system call exercise.

file1.c & file2.c: Code demonstrating the role of the Linker.

simple_program.c: Code demonstrating the role of the Loader.

Makefile: Script to compile all C files automatically.

answers.txt: Contains the theoretical answers regarding Linkers, Loaders, and process commands.
./p```
rocess_creation
