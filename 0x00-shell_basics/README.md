# SHELL
## What is shell
Shell is a program that takes command from the keybord and gives it to the operating system to perform.<br/>
Shell is interacted from the terminal<br/>
There are basic shell comands to work with.
## Navigation
This is using shell commands to navigate the terminal. <br/>
Before understanding this we must know the UNIX/LINUX file structure. <br>
Files in linux are arranged in _hierachial directory structure_<br/>
## Comands
1. __File Management__

| Commands | Description |
| ---| :---: |
..| Parent directory 
. | current directory
cd(-) | Navigate last directory
cd (~)/ cd | Navigate to home

2. __File Listing__

| commands | Description |
| ---: | :---:
 ls -a | List directory in long format
 ls -ld dir | Liist information about directory name instead of contents
ls -a | list files including hidden

_ls -f_: is a special file listing command that needs symbol to indicate type
| symbol | symbol name|
| :---: | ---|
@ | symbolic link
\* | executable
= | socket
\> | directory
\| | pipe
