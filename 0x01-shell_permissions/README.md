0. su is the command that switches current user

1. id -un prints the effective username of current user

2. sudo goups prints all groups the current user is part of

3. chown changes the owner of the to the user

4. touch creates the empty file

5. chmod u+x (file) writes a scriot that adds execute permissions to the owners (file)

6. chmod 754 hello (file) gives execute permission to owners, and only read permission to other users.

7. chmod a+u ./hello writes the script that adds execution permission to the owers (file)

8. chmod 007 hello writes the script thats sets thr permission to the (file)

9. chmod 753 hello writes the script that sets the mode of the (file)

10. chmod --reference=olleh hello writes the script sets the mode of the file hello the same as olleh’s mode.

11. chmod -R ugo+X creates the script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12. mkdir -m 751 my_dir Creates a script that creates a directory called my_dir with permissions 751 in the working directory.

13. chgrp school hello writes a script that changes the group owner to school for the file hello

14. chown -R: staff writes  a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.