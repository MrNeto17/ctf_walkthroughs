The objective is to find a password in a directory called inhere. The file containing the password is the only one with human-readable content (ASCII).

To achieve this, we start by navigating into the inhere directory using the cd inhere command. Then, we list the files in the directory with ls. Instead of using the cat command on each file individually to check their content, we simplify the process by using the file ./* command, which determines the type of content in each file.


![alt text](images/6.png)

From the output, we identify that the file with human-readable ASCII content is -file07. Finally, we use the command cat ./-file07 to display the password.