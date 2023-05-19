Write a simple UNIX command interpreter.
## What is the shell?
The shell is a program that takes commands from the keyboard via the terminal and gives them to the operating system to perform.
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
