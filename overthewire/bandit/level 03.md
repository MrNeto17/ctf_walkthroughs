# Finding pwd to level 4

Now, the objective is to find a password in a directory called inhere, but the file is hidden.
To find the hidden file we will use a trick by using the tab with cat command and a ".".

I listed the files in the home directory using the ls command and identified the directory named inhere. After navigating into it with "cd inhere", I listed the files inside using ls and noticed there were no files in it.
That result was predictable as we know that the file is hiden, so we typed "cat ." and used the auto-complete to get to the hidden file. 
Few other commands could give us this file, such as "ls -f" or "ls -a".


![alt text](images/5.png)


## Why ls doesn't show us the hidden file

By design, ls skips files starting with a . to reduce clutter and focus on non-hidden files.
Hidden files are often used for system configurations or temporary data.