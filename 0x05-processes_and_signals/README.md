0. #!/usr/bin/env bash
# This script  displays its PID.

echo $$. Writes a Bash script that displays its own PID.

1. #!/usr/bin/env bash
# This script displays list of currently running processes
# Must show all processes, for all users, including those which might not have a TTY
# Display a user-oriented format
# Show process hierarchy

ps -a -x -u -f. Write a Bash script that displays a list of currently running processes.

2.#!/usr/bin/env bash
# This script extends previous exercise command and displays line containing the bash word, this allowing you to easily get the PID of your Bash process
# You cannot use pgrep
# shellcheck disable=SC2009

./1-list_your_processes | grep "bash" ash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

3.#!/usr/bin/env bash
# This script displays the PID, along with process name of processes containing the word bash
# cannot use p s
pgrep -l bash Writes a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

4. #!/usr/bin/env bash
# This script displays a statement indefinitely
while true; do
    echo "To infinity and beyond"
        sleep 2
	done. Write a Bash script that displays To infinity and beyond indefinitely.

5. #!/usr/bin/env bash
# This script kills a process using command kill
kill "$(ps -x | pgrep -f beyond)" Writes a Bash script that stops 4-to_infinity_and_beyond process.


