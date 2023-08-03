su betty to change the current user to betty
whoami to print the current effective user
groups print all the groups that the user is part of
chown change the owner of the file
touch create an empty file
chmod +x to add excute permission to the file owner
chmod u+x,g+x,o+r to add multiple permissions
chmod +x to add execution permission for everybody
chmod 007 to set no permission for owner and group , all permission for others
chmod 753 to set permission to rwxr-x-wx
chmod --reference=olleh to copy the mode of this file
find . -type d -exec chmod a+x {} + find all subdirectories in the current directory and apply execute permissions
mkdir -m 751 my_dir to create a directory and give permission
chgrp school hello to change the group ownership
sudo chown -R vincent:staff . to change the owner and group for all files and dir in the working dir
