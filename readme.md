# Alex Billson's Really Average C++ Template

Use this if you want to avoid using an IDE and want to enjoy life I guess. Compied and pasted from Visual Studio's
layout of C++ projects. Basically structure your code as the following:

- Header Files
    - Place your .h files in here
    - Refer to these files in your Source code using the syntax `#include "../Header Files/filename.h"
- Resource Files
    - Put project resources in here
- Source Files
    - Your .cpp files go here

The solution is built to be used with a Linux system, thus the makefile. If you have Windows 10 then you can use the
Bash Subsystem like I do.
It requires the following to be installed:

- Make
    - `sudo apt-get install make -y`
- G++
    - `sudo apt-get install g++ -y`

Assuming both of these are installed, you can build an entire solution using the `make` command in your projects root
folder (the folder with this readme in it).

![Example](https://cdn.pbrd.co/images/COvNvb6JW.png)