Description
A simple UNIX shell which tries to emulate the standard UNIX shell (sh). Some additional functions were also added. This program is written in C. It is a project written in attempt to meet the requirements of the ALX Africa Software Engineering Program.

Installation
- Clone this repository into your working directory. 
- Compile the files with GCC using the following flags: -Wall -Wextra -Werror -pedantic -std=gnu89

Usage
The shell can run stand-alone, either in interactive or non-interactive mode.

Interactive Mode
- In interactive mode - Run the program, Wait for the prompt to appear and then you can go ahead to type in your commands
- Exit interactive mode with either "exit" or "ctrl-D".

Non-Interactive Mode
- Echo your desired command and pipe it into the program like this:

echo "ls" | ./shell

- The program will exit after finishing your desired command(s).

Included Built-Ins
The shell has support for the following built-in commands:

exit [n] - Exit the shell, with an optional exit status, n.
env	 - Print the environment.
setenv [var][value] - Set an environment variable and value. If the variable exists, the value will be updated.
unsetenv [var]	- Remove an environment variable.
cd [dir]	- Change the directory.
help [built-in]	- Read documentation for a built-in.

Credits

Amaditimi Precious and Mohamed Shoaeb Shoaeb.
