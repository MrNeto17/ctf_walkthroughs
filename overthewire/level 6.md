# Finding password for level 7

All we know is the password is in a file and the size, user and group owners of the file

owner group: bandit6
owner user: bandit7
size: 33bytes

Doing ls, ls -a and ls -a -l as shown bellow we saw that there was no file there with the specifications so we went back some directories with "cd .."

![alt text](images/8.png)


Now we will look for the file with the "find" command using -group and -user filters. We could go for -size also but being only level 6 we assumed the file will be easy to find with only this 2 parameters.

![alt text](images/9.png)


After looking through results and between all the errors we the file and used cat command to get the password
