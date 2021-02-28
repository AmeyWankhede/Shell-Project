# Linux-Shell-Project
- This is a self developed basic version of Bourne shell ("Bash") with multiple similar functionalities as well as many new ones.

## How to Use ?
- Download the source code to system in zip format or clone repo.
- Open up your terminal in Linux.
- Make sure you have GCC compiler installed.
- Compile the shellby using the command:
```
gcc ShellCode.c linkedlist.c utilities.c -o Shell.out
```
- Run by using command:
```
./Shell.out
```
- For list of commands,type:
```
help
```

## Logic Used
- Providing a few built-in functions, and seeing whether the command entered by user matches them. If yes, we call our custom function, or we call our sh_launch() function.
- Important concepts in C such as fork() ,exec() and concepts of processes and their ID's.

## Tech Stack used
- All the functionalities are programmed in C language with the help of libraries such as "sys/wait.h", "sys/types.h", "signal.h" ... etc.

## Results Obtained
- A fully working shell, which executes the normal functions of the default terminal, but also a few more custom functions created so that the power user can use it to his ability.
- All the functionalities used work smooth and bug-free.

## New additions
- `sh_google()` method : This method will help you search google with whatever query you provide next to it.
-  ***Usage*** : Simple `google` will open Google on your browser, and `google strings` will search strings on the same. You can also search for strings with multiple words separated by spaces.
- `sh_wikipedia` method :Similar to `sh_google` method,`wikipedia string` will search string on youtube.
