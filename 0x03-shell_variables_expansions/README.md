alias ls="rm *" -  script that creates an alias.

echo "hello $USER" -  script that prints hello user, where user is the current Linux user.

export PATH=$PATH:/action - /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) - a script that counts the number of directories in the PATH.

printenv - a script that lists environment variables.

set - a script that lists all local variables and environment variables, and functions.

BEST="School" -  a script that creates a new local variable.

export BEST=School - a script that creates a new global variable.

echo $(($TRUEKNOWLEDGE + 128)) -  a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.


