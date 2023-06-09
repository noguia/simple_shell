# What is the shell?
The shell is a program that takes commands from the keyboard via the terminal and gives them to the operating system to perform.

<h1 align="center">
	

![](https://i0.wp.com/akashicseer.com/wp-content/uploads/2020/12/baby-what-does-that-mean.jpeg?fit=253%2C260&ssl=1)

## About this project
This project is a simple version of the linux shell made for [ALX SE Program](https://www.alxafrica.com/software-engineering/) taking part of the "Low-level programming & Algorithms" projects.
It is created using the C programming Language and it can do many functionalities that a real shell does.
## Requirements
This shell is designed to run on `Ubuntu 20.04 LTS` using `gcc`, with the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
## Usage
**This shell supports both _interactive_ mode and _non-interactive_ mode.**

### Interactive mode
- Run the shell in the interactive mode: `./shell`

#### example:
```
vagrant@ubuntu-focal:~/simple_shell$ ./shell
$ echo Hello World!
Hello World!
$ exit
vagrant@ubuntu-focal:~/simple_shell$ 
```
### Non-interactive mode
- Run the shell in the non-interactive mode: `echo "ls" | ./shell`

#### example:
```
vagrant@ubuntu-focal:~/simple_shell$ echo -e "ls /var \n pwd" | ./shell
backups  cache  crash  lib  local  lock  log  mail  opt  run  snap  spool  tmp
/home/vagrant/simple_shell
vagrant@ubuntu-focal:~/simple_shell$ 
```
## General informations
- Used editors: `vim`
- Coding style: [Betty](https://github.com/holbertonschool/Betty/wiki)
- No known memory leaks ==> *hint: check with valgrind*
- No more than 5 functions per file

## Features
- [x] Display a prompt
- [x] Handle errors
- [x] Handle commands with arguments
- [x] Handle th PATH
- [ ] Write our own `getline` function
- [x] Write our own `strtok` function
- [x] Handle exit with status
- [ ] Handle commands separator `;`
- [ ] Handle logical operators `&&` and `||`
- [ ] Handle variables replacement, `$?` and `$$`
- [x] Handle comments `#`

## Builtins
- [x] `exit`
- [x] `env`
- [x] `setenv`
- [x] `unsetenv`
- [x] `cd`
- [ ] help
- [ ] history

## Allowed functions and syscalls
:computer: List of allowed functions and system calls :computer:
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- getpid (man 2 getpid)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)

## Project Done by:
> 1. [IBRAHIM OUHLIMA](https://github.com/noguia)
> 2. [smaail -K](https://github.com/smaail-k)

<p align="center">  
<img src ="https://assets.imaginablefutures.com/media/images/ALX_Logo.max-200x150.png">
</p>
