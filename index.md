## WEEK 2 LAB REPORT 1

1. **cd Command**
    - Command: `cd`
    - Outcome: C:\Users\Angel Medina>
    - Note: Changes directory to the user's home directory. There's no error with this command and it can be used from any directory.

2. **Navigating to the C: Drive**
    - Command: `cd C:`
    - Outcome: C:\>
    - Note: I navigated to the base level of the C: drive from C:\Users\Angel Medina>. There were no errors.

3. **Attempting to cd into hosts**
    - Command: `cd C:\Users\Angel Medina>`
    - Note: I received an error because `hosts` is a file, not a directory. You can't change directory to a file.

4. **Listing Contents with ls**
    - Command: `ls`
    - Note: After using Powershell, I saw the contents of the directory at C:\Users\Angel Medina>. It lists the files and directories in the current directory.

5. **Checking the /etc Contents**
    - Command: `ls /etc`
    - Note: This command shows some of the contents in the /etc directory. If there's an error, it could be because the directory doesn't exist or I don't have the permission to view its contents.

6. **Checking the /etc/hosts File**
    - Command: `ls /etc/hosts`
    - Note: This command checks the existence of the /etc/hosts file. However, there was an error on my Windows computer.

7. **Using cat Without a Specified File**
    - Command: `$ cat`
    - Note: This command is typically used in UNIX systems to display the content of files. But when used without arguments, it reads from the standard input. On my Windows system, I got an error because the directory couldn't be found.

8. **Trying to Display Directory Contents with cat**
    - Command: `$ cat /etc`
    - Note: I received an error because the cat command is designed to display the content of files, not directories. So when I specify /etc, I'm referencing a directory, not a file.

9. **Displaying the Content of /etc/hosts**
    - Command: `$ cat /etc/hosts`
    - Outcome: Displays content like "127.0.0.1   localhost"
    - Note: The /etc/hosts file is a system configuration file that maps hostnames to IP addresses.


![Image](example1.png)
![Image](example2.png)
![Image](example3.png)
![Image](example4.png)
![Image](example5.png)
![Image](example6.png)
![Image](example7.png)
![Image](example8.png)

