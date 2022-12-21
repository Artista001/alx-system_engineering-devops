0x03-shell_variables_expansions
alias ls='rm *' creates an alias with the name ls and the value rm *
echo "hello $USER" prints hello user, where user is the current Linux user.
PATH="$PATH:/action" adds /action to the PATH. /action
echo $PATH | tr ':' '\n' | WC -1 counts the number of directories in the PATH
printenv lists environment variables.
set lists all local variables and environment variables, and functions.
BEST="School" creates a new local variable. Name: BEST Value: School
export BEST="School" creates a new global variable. Name: BEST Value: School
echo $((128 + $TRUEKNOWLEDGE)) prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER/$DIVIDE)) prints the result of POWER divided by DIVIDE, followed by a new line.
echo $(($BREATH**$LOVE)) displays the result of BREATH to the power LOVE
echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo" prints all possible combinations of two letters, except oo.
