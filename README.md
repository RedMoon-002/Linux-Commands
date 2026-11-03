# Operating Systems Lab

A collection of Operating Systems lab experiments covering shell scripting, process management, CPU/memory/I/O behaviour, and virtual memory in Linux.

## Experiments

| # | Folder | Description |
|---|--------|-------------|
| 1 | [`exp1/`](exp1/) | Checks whether the argument passed is `0` and prints `True` or `False`. |
| 2 | [`exp2/`](exp2/) | Checks whether the argument is a file, a directory, or does not exist. |
| 3a | [`exp3a/`](exp3a/) | File/directory check with validation for a missing argument. |
| 3b | [`exp3b/`](exp3b/) | Renames the given files to uppercase filenames. |
| 4a | [`exp4a/`](exp4a/) | Calculates the total working time of a logged-in user. |
| 4b | [`exp4b/`](exp4b/) | Prints the lines of a file between two line numbers using `sed`. |
| 4c | [`exp4c/`](exp4c/) | Deletes lines containing a given word from one or more files. |
| 5 | [`exp5/`](exp5/) | String length and substring extraction in shell and C. |
| 6 | [`exp6/`](exp6/) | Allocates a user-specified amount of memory to observe memory usage. |
| 7a | [`exp7a/`](exp7a/) | CPU-bound process running an infinite counting loop. |
| 7b | [`exp7b/`](exp7b/) | I/O-bound process repeatedly writing to a file. |
| 9 | [`exp9/`](exp9/) | Process creation using `fork()` and `wait()`. |
| 10 | [`exp10/`](exp10/) | Prints PID and virtual address of a variable to study address spaces. |

Each experiment folder contains its own `README.md` with the aim, description, run instructions and sample output.

## Requirements

- Linux (tested on Ubuntu)
- `bash`, `gcc`
