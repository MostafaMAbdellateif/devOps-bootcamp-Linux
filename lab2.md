1. Using vi write your CV in the file mycv. Your CV should include your name, age, school, college, experience,...
- command -> vim mycv

	name: Mostafa Abdellatif 

	age: 24

	school: Al Bayan

	college: Computer Science

	experience: Software Engineer

	~                              

	:wq!

2. Open mycv file using vi command then: Without using arrows state how to:

	a. Move the cursor down one line at time.
    		- pressing J on keyboard
    		
	b. Move the cursor up one line at time.
    		- pressing K on keyboard
    		
	c. Search for word age
    		- write /age then press enter
	
	d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
    		- wrtie :5 then press enter
	
	e. Delete the line you are on and line 5.
    		- write :d then press enter
    		- move using cursor to line 5 and write :d then press number
	
	f. How to step to the end of line and change to writing mode in one-step.
    		- pressing A on keyboard (shift + a)

3. List the available shells in your system.
- command -> cat /etc/shells
- output -> /bin/bash
            /bin/csh
            /bin/dash
            /bin/ksh
            /bin/sh
            /bin/tcsh
            /bin/zsh

4. List the environment variables in your current shell.
- command -> env

5. List all of the environment variables for the bash shell.
- command -> printenv

6. What are the commands that list the value of a specific variable?
- command -> echo $VAR
- command -> echo "$VAR"
- command -> printenv VAR

7. Display your current shell name.
- command -> echo $SHELL
- command -> printenv SHELL

8. State the initialization files of: sh, ksh, bash.
- sh:
    1- /etc/profile (global)
    2- ~/.profile (current user "local")
- ksh:
    1- /etc/profile (global)
    2- ~/.profile (local)
    3- ~/.kshrc (local "if exist")
- bash:
    1- /etc/profile (global)
    2- ~/.bashrc (local)

9. Edit in your profile to display date at login and change your prompt permanently.
- nano .bashrc
- write (date) at the end of the file
- write (export 'PS1=mostafaTest$') at the end of the file to overwrite the default linux prompt
- press Ctrl+O to save
- press Ctrl+x to exit

10. Create a Bash shell alias named ls for the “ls –l” command.
- alias lsalias='ls -l'
