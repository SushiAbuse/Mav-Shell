# Mav-Shell
Mav Shell is similar to bourne shell (bash), in that it is a unix shell. That prompts for the users to enter a supported shell comamnd such as:

mkdir, ls, cd .., etc.

is executes the command and displays the output of the command. In addition this shell searches for any command in /bin, /usr/bin/, /usr/local/bin/ and the current working directory. Parameters may also be combined. 

Notes:
supports shell commands
pidhistory - list the PIDS of the last 15 processes spawned by the shell.
history - will list the last 15 commands entered by the user.
quit and exit - allows the user to exit the program
!n - where n is a number between 0 and 14 will result in your shell rerunning the nth command.

Contrants:
Mav Shell only supports up to 10 command line parameters in addition to the command.


Implementation:
Mav shell is implemented with fork(), wait(), and the exec family of functions
