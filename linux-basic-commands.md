
#### 01. This is to open new terminal in linux
> - ctrl + alt + t 

#### 02.  It displays present working directory
> - pwd

#### 03. This will take us to the home directory
> - cd

#### 04. This will take us to the home directory
> - cd ~ 

#### 05. This will go to the root directory
> - cd / 

#### 06. This double dot will take back one step back in the directory structure
> - cd .. 

#### 07. This will take us two folders back from current active directory
> - cd ../.. 

#### 08. This will take us inside My Books folder, when it has space in the folder name
> - cd My\ Books 

#### 09. We can use double quotes to specify folder name
> - cd “My Books” 

#### 10. For the same purpose, single quotes will work too
> - cd ‘My Books’ 

#### 11. This will give the list of all the files and directories in the present working directories
> - ls 

#### 12. This will allow you to exit from current running terminal session
> - exit

#### 13. list all the files and directories with more details
> - ls -alrt

#### 14. This will open new tab in browser and also in terminal
> - cmd + t

cmd + w (This will close current active tab)
ls <folder name> (This will display the list of files inside the folder specified)
ls / (This will display the all the files and directories in root directory)
ls ~ (This will all the files and directories in home directory)
ls .. (This will display all the list of files and directories one step back directory)
ls ../.. (This will give us list of all the files two directories back)
ls -l (This will give us list on long format)
ls -a (This will also list hidden files as well)
ls -lS (This will sort directory by their size, ascending order)
ls -al (Gives back the long list from root with permissions)
ls *html(This only displays all files with extension html)(* is called as wild character)
ls -lS > filename.txt (This will save the outcome of ls -lS command to this filename.txt file)
ls -R (This display all the subdirectories as well from the active directory)
cat filename.txt (This will display the content in file)
ls -d */ (List out all the directories only in the current active directory)
man ls (This will help with more description on how we can use specific command)
cat filename.txt (This will display content in filename.txt file)
cat filename01.txt filename02.txt (This displays two files contacts as well on terminal)
cat -b filename.txt (This will add the line number to the non blank line in the file)
cat  -n filename.txt (This will add line number to all the lines, including blank lines in the file)
cat -s filename.txt (this squeeze the more blank lines to one blank lines in the file, this won’t affect the content of the file, it just displays more ease way in the command prompt)
cat -e filename.txt (This will add $ at the end of each line)
cat > filename01.txt (This will allow us to write content to the file and save it, ctrl + d is to save and exit from the prompt after we finish writing content to the file. If we do the same command again and update the content, new content will replace the old one.Hence old content is gone)
cat >> filename.txt ( two >> will allow us to append new content to an earlier one, so we don’t lose the old content in the file.)
cat filename01.txt filename02.txt > outputfile.txt (This will allow us to save content in filename01 and filename02 to outputfile.txt file)
cat filename01.txt >> filename02.txt (This will transfer the content of filename01.txt to filename02.txt )
mkdir <directory-name> (This allow us to create a new directory)
mkdir <directory>/<directory> (This create a sub directory too)
mkdir -p folder01/folder02 (This can also create a new directory structure)
mkdir -p <folder01>/{folder02,folder03,folder04} (This create more directories inside folder01)(No space is required)
rmdir <directory-name> (This will remove the active directory)
rmdir -p <folder01/folder02/folder03> (This will remove all the directories in the structure)
rmdir -pv <folder01/folder02/folder03> (-v verbose tag helps us to see more backend information while executing)
rm -rv <dir01>/<dir02>/ (This will also remove all files inside /b directory)
cp <filename01.txt> <filename02> (This copies contents of filename01 to filename02. If filename02 doesn’t exist, it creates one and copies the contents to it.
cp <filename01.txt> <directory-name> (This will copy the current filename01.txt to the specified directory.
cp -i <filename01.txt> <filename02.txt> <directory-name> (This will allow us to not override the contents of filename01 to specified directory, since we already have filename01)(-i is an interactive mode)
cp -R <dir01> <dir02> (This copies all the contents in dir01 to dir02, because dir01 has contents in it)
cp -R <dir01> <dir02> (now dir01 will be copied to dir02, since all the contents in dir01 has already been copied to dir02)
cp -vR <dir-1> <dir02> (-v is verbose, this will give us steps of the execution in parallel)
mv <file01.txt> <file02.txt) ( this will change the name of the file and also contents of the file will remain the same. So we can use the move command to rename the file.)
mv <file01.txt> <dir01> (This will move file01.txt to directory dir01)
 mv <dir02> <dir03> (If dir03 doesn’t exist, it replaces dir02 to dir03 and moves the contents of dir02 to dir03) 
less <filename.txt> (This is used to read a specific contents in the file, down arrow, up arrow can be used to scroll the lines of the file in cmd line, B can be used to go pageup and space bar is page down, shift G is to get to top of the page)
touch <filename.txt> (This can be used to create a new empty file and also we can play around to change the timestamps of the directories)
nano <filename.txt> (This open up a nano text editor, follow the shortcuts on the editor creen to move around)
sudo (This will give access to admin privileges while executing few commands)
sudo -s (This will allow us to jump to root user in the terminal, -s is as super user)
top (This acts as a Task manager in windows, where we can check the cpu performance etc, we can kill the running processes with respective process id from top window with “k” stroke from keyboard)
pidof  <process-name> (This will give us respective process id number)
kill <process-id-number> (This will kill the process from execution)
kil -KILL <process-number> (This will kill the process forcefully)
kill -9 <process-id> (To kill the processes forcefully)
ps -ux (This will list all the running processes in system, we can processes is here as well)
ps -aux(This will show us all the running processes with more details including the user roles)
ps -U <user-name> (We can see processes running with their respective users in the system)
ps -C <process-name> (This will list out all the instances which are related to specific program/ process-name)
chmod o+x <file-name> (adding execute permission to other user)
chmod o+w <file-namer> ( adding write permission to other user)
chmod o+r <file-name> (adding read permission to other user)
chmod g+r <file-name> (adding group read permission to the file)
chmod g+x <file-name> (Adding group execute permission to the file)
chmod g-r <file-name? (It reduces the permission to execute and write but not read, we have removed the read permission to the file) (+ and - plays a role)
chmod ug=rwx <file-name> (This allow all permissions to both owner of this file and group of this file)
chmod ugo-rwx <file-name> (This removes all permissions to the mentioned file)
chmod a-rwx <file-name> (This command, a stands for all users and groups, hence it removes all permissions to all users and groups)
chmod u+rw, g=rw, o+r <file-name> (This will rw  permissions to user and group and only read permission to others, we have segregated the permission individually in this command)
chmod u-w <directory-name> (this will remove the write permission to the user)
ls -ld (This will bring up the list of directories in the current location)
chmod u-r <directory-name> (This will remove the read permission to the directory)
chmod u+r <directory-name> (added read permissions to the user for this directory)
chmod u-x <directory-name> (This will remove executable permissions to the user for this directory)
chmod 777 <file/directory-name> (777 will give you fill permissions, rwx. Read-Write-Executable)
chmod 000 <file-name> (This give no permissions to the file, so no one has permission to play with this file)
chmod 755 <file-name> (This will give full permissions to the user, read + executable permissions to group and others)
which bash (This command will give us the location of bash in system, either in unix or linux)
sh filename.sh (This is how we run the shell scripts in the terminal)
./filename.sh (This can also run the shell scripts)
which ls (This will bring me location of the ls executables in systems)
whatis <command-name> (This will give us short description about respective command)(whatis ip, whatis ls, whatis grep, whatis cat, etc)
sudo useradd <user-name> -m  -s /bin/bash -g users -c “we can provide comments for this user”
(This will add new user to the system, sudo is for the admin access while creating the user, -m will create a default home directory for the user, -s is meant for default shell which allow user to use shell functionalities /bin/bash, -g is default user flag)

ls /home (This will list all user from the home path)
sudo passwd <user-name> (This will allow us to change the user password for respective user)
sudo userdel <user-name> (This will just delete the user from the system, but not the home directory)
sudo userdel -r <user-name> (This will delete the user and also respective home directory, -r does the work)
sudo rm -r /home/<user-name> (This will remove all the data from the respective user)
groups (This will list all the current groups, where current user is connected to)
cat /etc/group (This will list all the groups available on the system, we can also find the file at /etc/groups)
sudo groupadd <new-group-name> (This will add a new group to the system)
sudo groupadd <group-name01> <groupname02> (This will add multiple new groups to the system)
sudo groupdel <group-name> (This will delete respective group from system)
sudo gpasswd -a <user-name> <group-name> (This will attach respective user to the respective group)
sudo gpasswd -d <user-name> <group-name> (This will detach the user from the group)
df (Show amount of disk space on file system)
df -h (This will show details in human readable formats)
du (This is used to estimates and display the disk space used by file system)
du -h (This will show disk usage details in human readable formats)
sudo du -sh (show the memory usage as well, with summary)
free (This will show total amount of free space, physical and cache memory)
free -h (free details in human readable format)
free -m (-m is mega bytes, -g gigabytes are irrelevant flags)
watch <any-command-name> (This command is used to run commands at regular intervals, very similar to cron jobs)
watch free -m
watch -n 1 free -m (-n is number is seconds, watch will run for every one sec of internal now)
watch -n 0.5 free -m (Now the time interval is for every  0.5 seconds)



-----------------------------------
