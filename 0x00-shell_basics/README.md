the #!/bin/bash script is used to instruct the operating system to use bash as a command interpreter
the pwd script prints the absolute path name of the current working directory.
the ls script displays the content list of your current directory
the cd script will change the working directory to the home directory of the specified user
the ls -l script displays current directory contents in long format
the ls -a -l script displays current directory contents, including hiddden files(starting with .) in the long format.
the ls -na script  displays current directory contents in long format, with user and group IDs displayed numerically and hidden files(starting with .) 
mkdir /tmp/myfirstdirectory creates the two directories
mv moves files and directories
rm deletes files
rm -r deletes directories
cd - changes the working directory to the previous one
ls -al . .. /boot  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile prints the type of the file named iamafile
ln -s /bin/ls __ls__ Creates a symbolic link to /bin/ls, named __ls__.
cp -rua *.html ../ Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
mv [A-Z]* /tmp/u Creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u
