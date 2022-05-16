
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

#### 15. This will close current active tab
> - cmd + w

#### 16. This will display the list of files inside the folder specified
> - ls /folder name/

#### 17. This will display the all the files and directories in root directory
> - ls /

#### 18. This will all the files and directories in home directory
> - ls ~ 

#### 19. This will display all the list of files and directories one step back directory
> - ls ..

#### 20. This will give us list of all the files two directories back
> - ls ../.. 

#### 21. This will give us list on long format
> - ls -l
 
#### 22. This will also list hidden files as well
> - ls -a 

#### 23. This will sort directory by their size, ascending order
> -ls -lS
 
#### 24. Gives back the long list from root with permissions
> - ls -al
 
#### 25. This only displays all files with extension html)(* is called as wild character
> - ls *html 

#### 26. This will save the outcome of ls -lS command to this filename.txt file
> - ls -lS > filename.txt
 
#### 27. This display all the subdirectories as well from the active directory
> - ls -R

#### 28. This will display the content in file
> - cat filename.txt

#### 29. List out all the directories only in the current active directory
> - ls -d */

#### 30. This will help with more description on how we can use specific command
> - man ls

#### 31. This will display content in filename.txt file
> - cat filename.txt 

#### 32. This displays two files contacts as well on terminal
> - cat filename01.txt filename02.txt 

#### 33. This will add the line number to the non blank line in the file
> - cat -b filename.txt 

#### 34. This will add line number to all the lines, including blank lines in the file
> - cat  -n filename.txt 

#### 35. This squeeze the more blank lines to one blank lines in the file, this won’t affect the content of the file, it just displays more ease way in the command prompt
> - cat -s filename.txt

#### 36. This will add $ at the end of each line
> - cat -e filename.txt

#### 37. This will allow us to write content to the file and save it, ctrl + d is to save and exit from the prompt after we finish writing content to the file. If we do the same command again and update the content, new content will replace the old one.Hence old content is gone
> - cat > filename01.txt

#### 38. two >> will allow us to append new content to an earlier one, so we don’t lose the old content in the file.
> - cat >> filename.txt

#### 39. This will allow us to save content in filename01 and filename02 to outputfile.txt file
> - cat filename01.txt filename02.txt > outputfile.txt 

#### 40. This will transfer the content of filename01.txt to filename02.txt 
> - cat filename01.txt >> filename02.txt 

#### 41. This allow us to create a new directory
> - mkdir /directory-name/ 

#### 42. This create a sub directory too
> - mkdir directory/directory/

#### 43. This can also create a new directory structure
> - mkdir -p folder01/folder02 

#### 44. This create more directories inside folder01)(No space is required
> - mkdir -p /folder01/{folder02,folder03,folder04} 

#### 45. This will remove the active directory
> - rmdir /directory-name/

#### 46. This will remove all the directories in the structure
> - rmdir -p /folder01/folder02/folder03/ 

#### 47. -v verbose tag helps us to see more backend information while executing
> - rmdir -pv /folder01/folder02/folder03/ 

#### 48. This will also remove all files inside /b directory
> - rm -rv <dir01>/<dir02>/ 

#### 49. This copies contents of filename01 to filename02. If filename02 doesn’t exist, it creates one and copies the contents to it.
> - cp /filename01.txt/  /filename02/ 

#### 50. This will copy the current filename01.txt to the specified directory.
> - cp /filename01.txt/ /directory-name/ 

#### 51. This will allow us to not override the contents of filename01 to specified directory, since we already have filename01)(-i is an interactive mode) 
> - cp -i /filename01.txt/ /filename02.txt/ /directory-name/

#### 52. This copies all the contents in dir01 to dir02, because dir01 has contents in it.
> - cp -R /dir01/ /dir02/

#### 53. now dir01 will be copied to dir02, since all the contents in dir01 has already been copied to dir02
> - cp -R /dir01/  /dir02/ 

#### 54. -v is verbose, this will give us steps of the execution in parallel
> - cp -vR /dir-1/ /dir02/

#### 55. This will change the name of the file and also contents of the file will remain the same. So we can use the move command to rename the file.
> - mv /file01.txt/ /file02.txt/ 

#### 56. This will move file01.txt to directory dir01
> - mv /file01.txt/ /dir01/ 

#### 57. If dir03 doesn’t exist, it replaces dir02 to dir03 and moves the contents of dir02 to dir03)
> - mv /dir02/ /dir03/

#### 58. This is used to read a specific contents in the file, down arrow, up arrow can be used to scroll the lines of the file in cmd line, B can be used to go pageup and space bar is page down, shift G is to get to top of the page
> - less /filename.txt/ 

#### 59. This can be used to create a new empty file and also we can play around to change the timestamps of the directories
> - touch /filename.txt/ 

#### 60. This open up a nano text editor, follow the shortcuts on the editor creen to move around
> - nano /filename.txt/

#### 61. This will give access to admin privileges while executing few commands
> - sudo

#### 62. This will allow us to jump to root user in the terminal, -s is as super user
> - sudo -s 
#### 63. This acts as a Task manager in windows, where we can check the cpu performance etc, we can kill the running processes with respective process id from top window with “k” stroke from keyboard
> - top 

#### 64. This will give us respective process id number
> - pidof  /process-name/ 

#### 65. This will kill the process from execution
> - kill /process-id-number/ 

#### 66. This will kill the process forcefully
> - kil -KILL /process-number/

#### 67. To kill the processes forcefully
> - kill -9 /process-id/ 

#### 68. This will list all the running processes in system, we can processes is here as well
> - ps -ux 

#### 69. This will show us all the running processes with more details including the user roles) 
> - ps -aux

#### 70. We can see processes running with their respective users in the system
> - ps -U /user-name/ 

#### 71. This will list out all the instances which are related to specific program/ process-name
> - ps -C /process-name/

#### 72. Adding execute permission to other user
> - chmod o+x /file-name/ 

#### 73. Adding write permission to other user
> - chmod o+w /file-name/ 

#### 74. Adding read permission to other user
> - chmod o+r /file-name/

#### 75. Adding group read permission to the file
> - chmod g+r /file-name/ 

#### 76. Adding group execute permission to the file
> - chmod g+x /file-name/ 

#### 77. It reduces the permission to execute and write but not read, we have removed the read permission to the file) (+ and - plays a role
> - chmod g-r /file-name/ 

#### 78. This allow all permissions to both owner of this file and group of this file
> - chmod ug=rwx /file-name/ 

#### 79. This removes all permissions to the mentioned file
> - chmod ugo-rwx /file-name/ 

#### 80. This command, a stands for all users and groups, hence it removes all permissions to all users and groups
> - chmod a-rwx /file-name/ 

#### 81. This will rw  permissions to user and group and only read permission to others, we have segregated the permission individually in this command 
> - chmod u+rw, g=rw, o+r /file-name/ 

#### 82. this will remove the write permission to the user
> - chmod u-w /directory-name/ 

#### 83. This will bring up the list of directories in the current location
> - ls -ld 

#### 84. This will remove the read permission to the directory
> - chmod u-r /directory-name/ 

#### 85. Added read permissions to the user for this directory
> - chmod u+r /directory-name/ 

#### 86. This will remove executable permissions to the user for this directory)
> -chmod u-x /directory-name/ 

#### 87. 777 will give you fill permissions, rwx. Read-Write-Executable
> - chmod 777 /file/directory-name/ 

#### 88. This give no permissions to the file, so no one has permission to play with this file
> - chmod 000 /file-name/

#### 89. This will give full permissions to the user, read + executable permissions to group and others
> - chmod 755 /file-name/

#### 90. This command will give us the location of bash in system, either in unix or linux
> - which bash 

#### 91. This is how we run the shell scripts in the terminal
> - sh filename.sh 

#### 92. This can also run the shell scripts
> - ./filename.sh 

#### 93. This will bring me location of the ls executables in systems
> - which ls 

#### 94. This will give us short description about respective command)(whatis ip, whatis ls, whatis grep, whatis cat, etc
> - whatis /command-name/ 

#### 95. This will add new user to the system, sudo is for the admin access while creating the user, -m will create a default home directory for the user, -s is meant for default shell which allow user to use shell functionalities /bin/bash, -g is default user flag
> - sudo useradd <user-name> -m  -s /bin/bash -g users -c “we can provide comments for this user”

#### 96. This will list all user from the home path
> - ls /home

#### 97. This will allow us to change the user password for respective user
> - sudo passwd /user-name/ 

#### 98. This will just delete the user from the system, but not the home directory
> - sudo userdel /user-name/ 

#### 99. This will delete the user and also respective home directory, -r does the work
> - sudo userdel -r /user-name/ 

#### 100. This will remove all the data from the respective user
> - sudo rm -r /home/user-name/ 

#### 101. This will list all the current groups, where current user is connected to
> - groups 

#### 102. This will list all the groups available on the system, we can also find the file at /etc/groups
> - cat /etc/group 

#### 103. This will add a new group to the system
> - sudo groupadd /new-group-name/ 

#### 104. This will add multiple new groups to the system
> - sudo groupadd /group-name01/ /groupname02/ 

#### 105. This will delete respective group from system
> - sudo groupdel /group-name/ 

#### 106. This will attach respective user to the respective group
> - sudo gpasswd -a /user-name/ /group-name/ 

#### 107. This will detach the user from the group
> - sudo gpasswd -d /user-name/ /group-name/ 

#### 108. Show amount of disk space on file system 
> - df 

#### 109. This will show details in human readable formats
> - df -h

#### 110. This is used to estimates and display the disk space used by file system 
> - du

#### 111. This will show disk usage details in human readable formats
> - du -h 

#### 112. Show the memory usage as well, with summary
> - sudo du -sh 

#### 13. This will show total amount of free space, physical and cache memory
> - free 

#### 114. Free details in human readable format
> - free -h 

#### 115. -m is mega bytes, -g gigabytes are irrelevant flags 
> - free -m 

#### 116. This command is used to run commands at regular intervals, very similar to cron jobs
> - watch /any-command-name/ 

#### 117. watch command is a built-in Linux utility used for running user-defined commands at regular intervals
> - watch free -m

#### 118. -n is number is seconds, watch will run for every one sec of internal now
> - watch -n 1 free -m 

#### 119. Now the time interval is for every  0.5 seconds
> - watch -n 0.5 free -m 



-----------------------------------


































