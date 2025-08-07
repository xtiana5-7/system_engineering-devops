# 0x05. Processes and Signals

This project introduces Linux process management and the use of signals in the shell. It covers how to find process IDs, list running processes, and send signals to control those processes using Bash scripts.

## Tasks Covered

### 0. What is my PID
A Bash script that displays its own process ID using `$$`.

### 1. List your processes
A script that displays a list of currently running processes for the current user.

### 2. Show your Bash PID
A script that displays the PID of the Bash process executing the script.

### 3. Show your Bash PID using ps
A script that uses `ps` to get the PID of the current Bash shell.

### 4. To infinity and beyond
A script that creates an infinite loop printing "To infinity and beyond".

### 5. Kill me now
A script that stops the `4-to_infinity_and_beyond` process using `kill`.

### 6. Kill me now made easy
A script that stops the `4-to_infinity_and_beyond` process using `pkill`.

### 7. Highlander
A script that displays "To infinity and beyond" indefinitely, but can be stopped gracefully using `SIGTERM`.

### 8. Beheaded process
A script that kills a process by name using `kill -9`.

### 9. Process and PID file
A script that saves its PID into a file and prints messages periodically.

## General Requirements

- All Bash scripts start with `#!/usr/bin/env bash`
- The second line is a comment explaining what the script does
- All scripts are executable with the correct permissions

## Author

**Oladele Oluwafunmike Christianah**

GitHub: [@christianah05](https://github.com/christianah05)

