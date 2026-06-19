
Kernel is the heart of the OS. It is the direct controller of the hardware that makes up the computer (CPU, memory, files, network...)
? Is the scheduler part of the kernel or just a program that collaborates with the kernel?

Shell is the command interpreter for the kernel. All the linux commands are actually programs and utilities which the shell passes on  (interpretes) for the kernel to execute. The kernel passes the result of the execution (if needed by user) back to the shell
So the shell is like means by which the user communicates with the kernel

The terminal (like its physical counterpart) does not have processing power in the real sense. It is just like window via which the shell is made available to the user. So the terminal receives provides the user with a "place" to type in the commands and also to read the response coming from either the Shell or the kernel via the Shell

A distribution is necessary because the kernel on its own cannot do anything. It is like an engine (kernel) with a car (distritubion also called distro). One needs many accessories inorder for the engine to actually be useful to the user. So the distro packages all the necessary programs and utilities and configurations necessary for the OS to work on a computer.

Examples of Distros

Ubuntu is beginner friendly and is based on debian (extremely stable)
Debian
Redhat: Linux for enterprise use. Need for stability and support for enterprises covered.
Fedory: Redhat for the ordinary users?