# Working through the first module, Bandit, on Over-the-Wire

**#Level 0**\
**#Connect to bandit.labs.overthewire.org on port 2220 using ssh, with username = bandit0 and password = bandit0.**

![Bandit0 SSH Screenshot](image.png)

**#Level 1**\
**#Retrieve password from readme file and use to ssh into bandit1**

![bandit0 password Retrieval](image-1.png)

![Passwords.txt](image-2.png)

![Bandit1](image-3.png)

**#Level 2**\
**#Retrieve the password from the - file, which is the password for bandit2. The trick here is knowing how to open a file that begins with -.**

![bandit2 password retrieval](image-4.png)

**#Level 3**\
**Retrieve password from "spaces in file name" which is stored on bandit2**

![bandit3 password retrieval](image-5.png)

**#Level 4**\
**Retrieve password from the hidden file stored in the inhere directory. Using the -a option on the ls command will reveal hidden files.**

![bandit4 password retrieval](image-6.png)

**Level 5**\
**Retrieve password from the only human-readable file in the directory. The challenge here is determining the correct file. We can use the file command to print out file types for us**

![file command](image-7.png)
![bandit5 password retrieval](image-8.png)

**Level 6**\
**Retrieve password from the only human-readable, non executable, and 1033 bytes in size**

![bandit6 password retrieval](image-9.png)

**Level 7**\
**Retrieve password stored somewhere on the server that is owned by user bandit7, owned by group bandit6, and 33 bytes in size.**

![find command1](image-10.png)

**use 2> /dev/null to filter out errors**
![find command2](image-11.png)

**Level 8**\
**Retrieve password from the data.txt file where the password is next to the word millionth. We will use the grep command to find it.**

![bandit7 password retrieval](image-12.png)

**Level 9**\
**Retrieve the only unique password from the data.txt file. This requires the use of the sort and uniq command**

![bandit8 password retrieval](image-13.png)

**Level 10**\
**Retrieve password from the data.txt file that is one of the few human-readable strings, preceded by several '=' characters.**

![bandit9 password retrieval](image-14.png)