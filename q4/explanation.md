# Q4 Explanation

- `lsof` displayed the currently open files and descriptors, which helped identify active file access in the shell.
- `exec 3<app.log` opened the sample log file on file descriptor 3, illustrating how Linux associates files with numeric descriptors.
- Redirecting output and error streams with `>`, `2>`, and `2>&1` showed how standard output and standard error are handled separately.
- `ulimit -a` displayed shell resource limits such as open files and stack size, which influence process and I/O behavior.
