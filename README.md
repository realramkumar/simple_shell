Simple shell in C
=================

Shell is a program used to access the OS system calls.

Here is a simple program which uses fork and execvp to illustrate it.

```
$gcc simple_shell.c -o shell
$./shell
>ls
README.md  shell  simple_shell.c
>mkdir test
>ls
README.md  shell  simple_shell.c  test
>cd test
>pwd
/home/intern/codez/shell/test
>cd ..
>pwd
/home/intern/codez/shell
>rm -rf test
>ls
README.md  shell  simple_shell.c
>head -5 simple_shell.c
#include <stdio.h>
#include <stdlib.h>
#include <unistd.h>

#define SIZE 10
>exit
$
```
