The objective was to find a password in a directory called inhere. The file containing the password was the only one with human-readable content (ASCII).

To achieve this, I started by navigating into the inhere directory using the cd inhere command. Then, I listed the files in the directory with ls. Instead of using the cat command on each file individually to check their content, I simplified the process by using the file ./* command, which determines the type of content in each file.

![alt text](images/6.png)

From the output, I identified that the file with human-readable ASCII content was -file07. Finally, I used the command cat ./-file07 to display the password.