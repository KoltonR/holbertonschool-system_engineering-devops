0.(echo Hello), World prints “Hello, World”, followed by a new line to the standard output.

1.(echo -e "\"(\uOod4o)'") Write a script that displays a confused smiley "(Ôo)'

2.(cat /etc/passwd) Display the content of the /etc/passwd file.

3.cat /etc//paswd /etc/host is the Display the content of /etc/passwd and /etc/hosts

4.tail /etc/passwd Display the last 10 lines of /etc/passwd

5.head /etc/passwd Display the first 10 lines of /etc/passwd

6. head -n 3 iacta|tail -n 1 Write a script that displays the third line of the file iacta.

7.echo "Best School" > '\*\\'"'"'"Best School"\'"'"'\\*$\?\*\*\*\*\*:)'
Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)

8.ls -la > ls_cwd_content Writes a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

9.tail -n 1 iacta >> iacta Writes a script that duplicates the last line of the file iacta

10.find . -type f -name '*.js' -delete Writes a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

11.find . -mindepth 1 -type d | wc -l Write a script that counts the number of directories and sub-directories in the current directory.

12.ls -1t | head script that displays the 10 newest files in the current directory.

13.sort | uniq -u cript that takes a list of words as input and prints only words that appear exactly once.

14.cat /etc/passwd | grep root Display lines containing the pattern “root” from the file /etc/passwd

15.cat /etc/passwd | grep bin | wc -l Display the number of lines that contain the pattern “bin” in the file /etc/passwd

16.cat /etc/passwd | grep -A3 root Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

17.cat /etc/passwd | grep -v bin Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

18.cat /etc/ssh/sshd_config | grep -i '^[a-z]' Display all lines of the file /etc/ssh/sshd_config starting with a letter.

19.tr 'A' 'Z' | tr 'c' 'e' Replace all characters A and c from input to Z and e respectively.

20.tr -d 'cC' Create a script that removes all letters c and C from input.

21.rev Write a script that reverse its input.

22.cat /etc/passwd | cut -d: -f1,6 | sort Write a script that displays all users and their home directories, sorted by users.



