alias ls='rm *' creates an alias

echo hello $USER prints hello user, where user is the current Linux users

export PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program

echo $PATH | tr : "\n" | wc -l counts the number of directories in the PATH

printenv | less Create a script that lists environment variables.

set | less lists all local variables and environment variables, and functions.- BEST="School" creates a new local variable.

export BEST="School" Create a script that creates a new global variable.

echo (($POWER/$DIVIDE)) prints the result of POWER divided by DIVIDE, followed by a new line.

echo $(($BREATH**$LOVE)) displays the result of BREATH to the power LOVE.

echo $((2#$BINARY)) converts a number from base 2 to base 10.

echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" prints all possible combinations of two letters, except oo.

printf "%.2f\n" $NUM prints a number with two decimal places, followed by a new line.

printf "%x\n" $DECIMAL converts a number from base 10 to base 16.

tr 'A-Za-z' 'N-ZA-Mn-za-m' encodes and decodes text using the rot13 encryption. Assume ASCII.

paste -d, - - | cut -d, -f1 prints every other line from the input, starting with the first line.

printf "%o\n" ((5#$(echo ((5#$(echo $STIR | tr stir. 01234))) )) | tr 01234567 bestchol adds the two numbers stored in the environment variables WATER and STIR and prints the result.
