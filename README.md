# Pipex

## 🚀 Project Overview
**Pipex** is a C-based project that simulates the functionality of the Unix pipeline, allowing you to understand and implement inter-process communication through pipes. This project tests your grasp of low-level system programming, specifically how processes interact with each other using Unix system calls.

## 🛠 Skills and Knowledge Gained
### Core Programming Skills
- **Mastering System Calls**: Hands-on experience with core Unix system calls such as `open`, `close`, `read`, `write`, `dup`, `dup2`, `fork`, `pipe`, `execve`, and `wait`.
- **Error Handling**: Strengthened ability to write error-resistant code by handling system errors gracefully and ensuring that the program exits with meaningful error messages.
- **Memory Management**: Gained expertise in dynamic memory allocation using `malloc` and `free` to manage resources efficiently and prevent memory leaks.

### Inter-Process Communication
- **Pipes and Redirection**: Implemented bidirectional communication between processes through pipes, understanding how data flows through them and the necessary system calls (`pipe`, `dup`, `dup2`) to achieve redirection.
- **Fork and Exec**: Applied `fork` to create child processes and `execve` to execute commands in those processes, enhancing knowledge of process management in C.
- **Synchronization and Waiting**: Used `wait` and `waitpid` to manage process synchronization and handle process termination effectively.

### Algorithmic Problem Solving
- **Command Execution Parsing**: Built logic to parse and execute shell commands, including handling command-line arguments and constructing process pipelines.
- **Error Prevention and Debugging**: Developed methods to catch potential issues such as segmentation faults and memory errors, reinforcing debugging skills in C.
- **File Handling**: Applied file operations (`open`, `close`, `read`, `write`) to manage input and output streams, ensuring data is read from and written to files correctly.

### Build and Deployment
- **Makefile Creation**: Developed an automated `Makefile` to compile the project with the necessary flags (`-Wall`, `-Wextra`, `-Werror`), ensuring reproducible builds without unnecessary relinking.
- **Libft Integration**: Incorporated the `libft` library (if applicable) to handle custom functions not provided by the standard C library.
- **Cross-Platform Compatibility**: Ensured compatibility with the development environment, enabling seamless operation on Unix-based systems.

## 📜 Installation and Setup

### Prerequisites
Ensure you have the following installed:
- A C compiler like `gcc`
- The `libft` library (if applicable)
- `make` to build the project

### How to Use
Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/AndrePortfolio/pipex.git
cd pipex
make
./pipex <file1> <cmd1 args> <cmd2 args> <file2>
