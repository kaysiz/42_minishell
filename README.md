## Project Instructions

### Mandatory

- Can only use C
- Must respect the school imposed coding style ([The Norme][norme-pdf])
- No memory leaks
- Implement a series of builtins: `echo`, `cd`, `setenv`, `unsetenv`, `env`, `exit`
- Manage the errors without using `errno`, by displaying a message adapted
to the error output
- Can only use these standard library functions:
    - malloc, free
    - access
    - open, close, read, write
    - opendir, readdir, closedir
    - getcwd, chdir
    - stat, lstat, fstat
    - fork, execve
    - wait, waitpid, wait3, wait4
    - signal, kill
    - exit
- Must have a Makefile to build the program
- The binary file must be named `minishell`
- Can use [Libft][libft-url]
- Handle program interruption (Ctrl + D)
- [Click here][1] for the rest

### Bonuses

- Signal management (specifically Ctrl + C)
- PATH's right management (error handling)
- Multiple commands (semi colons)
