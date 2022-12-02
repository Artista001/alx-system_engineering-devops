cd betty/ is a script that switches the current user to the user betty
whoami script prints the effective username of the current user
groups script that prints all the groups the current user is part of
chown script changes the owner of a file to different user
touch script creates a new empty file
chmod u+x script adds execute permissions to the owner of the file
chmod a+x script adds execution permission to the owner, the group owner and the other users, to the file
chmod o+rwx script gives the owner and group members no permission at all but grants other user all the permission to the file
chmod 753 script sets the mode of a file to - rwxr-x-wx
chmod 664 script sets the mode of a file to - rw-rw-r--
mkdir 751 script creates a directory with permissions 751 in the working directory
