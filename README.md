# Unhandled File Processing Error in Bash Script

This repository demonstrates a common error in bash scripting: failing to check the exit status of commands like 'cat'.  The provided `bug.sh` script attempts to read a file without error handling, which can lead to unexpected behavior or script crashes if the file is not found or inaccessible.

The `bugSolution.sh` script shows the correct approach, incorporating error checking using exit status codes.