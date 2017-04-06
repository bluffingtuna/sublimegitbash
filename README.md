# sublimegitbash
this will add a new command line, subl, to open files with sublime text within git bash.

First, you need to create .bash_profile under /users/username directory.

this will set the PATH and other environmental variables for the shell.

and then edit with sublime or notepad the .bash_profile file and add the below command

#### alias subl="C:/Program\ Files/Sublime\ Text\ 3/sublime_text.exe"




-----------------------------------------
# Shortcut!!!
-----------------------------------------



you can simply open your git bash and type the below command to create the modified .bash_profile in your home directory.

#### echo 'alias subl="C:/Program\ Files/Sublime\ Text\ 3/sublime_text.exe"' >> ~/.bash_profile


This will only work if you are logged in via console. if you want the add the alias for every users, you can create .bashrc file instead


#### echo 'alias subl="C:/Program\ Files/Sublime\ Text\ 3/sublime_text.exe"' >> ~/.bashrc


you can download .modified .bashsrc and .bash_profile and paste it on your home folder as well(/users/username)

you can check your home folder by typing echo ~ in your git bash.

http://www.joshstaiger.org/archives/2005/07/bash_profile_vs.html

the link above explains the difference between bash_profile and bashrc