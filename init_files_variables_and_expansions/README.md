 the shell. The process that makes this happen is called expansion. With expansion, we type something and it is expanded into something else before the shell acts upon it. To demonstrate what we mean by this, let's take a look at the echo command. echo is a shell builtin that performs a very simple task. It prints out its text arguments on standard output:

[me@linuxbox me]$ echo this is a test
this is a test

## Shell Arithmetic

The shell allows arithmetic expressions to be evaluated, as one of the shell expansions or by using the (( compound command, the let and declare builtins, the arithmetic for command, the [[ conditional command, or the -i option to the declare builtin.

## The alias Command

MThe alias command makes it possible to launch any command or group of commands (inclusive of any options, arguments and redirection) by entering a pre-set string (i.e., sequence of characters).

That is, it allows a user to create simple names or abbreviations (even consisting of just a single character) for commands regardless of how complex the original commands are and then use them in the same way that ordinary commands are used.

A command is an instruction given by a user to tell a computer to do something. Commands are generally issued by typing them in at the command line (i.e., an all-text user interface) and then pressing the ENTER key, which passes them to the shell. A shell is a program that provides the traditional, text-only user interface for a Unix-like operating systems. Its primary function is to read commands and then execute (i.e., run) them.~