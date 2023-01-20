0. alias ls='rm *' creates the script that creates an alias Creates a script that creates an alias.

1. echo "hello MyUser$(whomai)" script that prints hello user, where user is the current Linux user.

2. export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/action  should be the last directory the shell looks into when looking for a program

3. echo $PATH | tr -s ':' '\n' | wc -l script that counts the number of directories in the PATH.

4. printenv script that lists environment variables.

5. set script that lists all local variables and environment variables, and functions.

6. BEST=School a script that creates a new local variable.

7. export BEST="School" Create a script that creates a new global variable.

8. echo $((128+$TRUEKNOWLEDGE)) Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

9. echo $(($POWER/$DIVIDE)) Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

10. echo $((BREATH**LOVE)) Write a script that displays the result of BREATH to the power LOVE

11. echo $((2#BINARY)) Write a script that converts a number from base 2 to base 10.

12. echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo Create a script that prints all possible combinations of two letters, except oo.

13. printf "%0.2f\n" $NUM Write a script that prints a number with two decimal places, followed by a new line.



