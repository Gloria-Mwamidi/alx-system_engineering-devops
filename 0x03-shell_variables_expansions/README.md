Create a script that creates an alias.-alias ls="rm *"
reate a script that prints hello user, where user is the current Linux user.-echo "hello" $USER
dd /action to the PATH. /action should be the last directory the shell looks into when looking for a program.-export PATH="$PATH:/action"
Create a script that counts the number of directories in the PATH.-echo $PATH | tr -s ":" "\n" | wc -l
Create a script that lists environment variables.-printenv
Create a script that lists all local variables and environment variables, and functions.-set 
Create a script that creates a new local variable.-BETTY="Holberton"
Create a script that creates a new global variable.-export HOLBERTON="Betty"
Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.--e $((128 + TRUEKNOWLEDGE))
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.-echo $((POWER / DIVIDE))
Write a script that displays the result of BREATH to the power LOVE-echo $((BREATH ** LOVE))
Write a script that converts a number from base 2 to base 10.-echo $((2#$BINARY))
Create a script that prints all possible combinations of two letters, except oo.-printf "%s\n" {a..z}{a..z} | grep -v "oo"
Write a script that prints a number with two decimal places, followed by a new line.-printf "%0.2f\n" $NUM
Write a script that converts a number from base 10 to base 16.-printf '%x\n' $DECIMAL

