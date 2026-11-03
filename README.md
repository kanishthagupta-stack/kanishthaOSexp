Operating System Lab Experiments
This repository contains 11 Operating System lab experiments using Bash/Shell Script and C, intended for Linux/Ubuntu or Ubuntu in VirtualBox.

Title note: Some handwriting in the supplied index is difficult to read. The topics below follow the readable parts and use standard OS-lab interpretations for unclear wording. Confirm the exact wording of Experiments 3–7 with your lab manual if exact title matching is required.

Experiment index
Basic Bash commands, pipes, file/directory operations, and searching
Bash commands
Test, data, and text-processing commands
Shell script using command-line arguments and file checks
Shell script to display and filter file contents
Shell script using string tests and menu options
C program to display command-line arguments
CPU-bound and I/O-bound processes; observe CPU usage
Observe process memory maps
Display parent/child process IDs and variable addresses
Create a child process using fork()

Requirements
Install GCC on Ubuntu:

sudo apt update
sudo apt install build-essential
Running a shell script
cd experiment-01
chmod +x *.sh
./commands.sh
Compiling a C program
cd experiment-07
gcc arguments.c -o arguments
./arguments hello 123
Each experiment folder includes its own README with aim, explanation, run instructions, sample output, and result. Output shown is illustrative; process IDs and memory addresses vary.

Safety: Experiment 8 intentionally uses CPU time. Stop it with Ctrl+C and do not run load demonstrations on production/shared machines.
