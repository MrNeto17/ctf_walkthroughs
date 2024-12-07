# Finding flag for level 12

In this exercise I had again the flag in a data.txt but this time it each character was rotated 13 times.

1. **Getting encoded string:**

   Even though there are ways to decode a Caesar cipher directly in the Linux terminal, I took this opportunity to brush up on Python. First, I retrieved the encoded message with the following command:
    
    `cat data.txt`

![alt text](images/18.png)

2. **Making the Script and getting the flag:**

    After retrieving the encoded message, I created a small Python script on my machine to decrypt the Caesar cipher, allowing input for the encoded message and the shift. Here's the script:

![alt text](images/17.png)

![alt text](images/18.png)