1. Install Ubunto OS using virtal machine.
- done

2. What is the difference between cat and more command?
- cat -> display all the file content at once
- more -> display the content part by part, intially it displys the first part and by pressing space it will reval the next part...and so on

3. What is the difference between rm and rmdir using man?
- rm -> remove files and can delete any type of directories if passed certain option (-r)
- rmdir -> remove only empty directories

4. Copy the /etc/passwd file to your home directory making its name is mypasswd.
- cp /etc/passwd ~/mypasswd

5. Rename this new file to be oldpasswd.
- mv ~/mypasswd ~/oldpasswd

6. You are in /usr/bin, list four ways to go to your home directory
- cd ~
- cd /home/mostafaabdellatif
- cd ../../home/mostafaabdellatif
- cd

7. List Linux commands in /usr/bin that start with letter w
- command -> ls /usr/bin | grep ^w

8. Display the first 4 lines of /etc/passwd
- command -> head -4 /etc/passwd

9. Display the last 7 lines of /etc/passwd
- command -> tail -7 /etc/passwd

10. Display the man pages of passwd the command and the file sequentially in one command.
- command -> man passwd; cat /etc/passwd

11. Display the man page of the passwd file.
- command -> man /etc/passwd

12. Display a list of all the commands that contain the keyword passwd in their man page.
- man -k passwd