1st: Cd command Example of the cd command with no arguments: It will show :C:\Users\Angel Medina> Changes directory to the home directory. Not an error. It could work at any directory 
#2 I am using Windows, so I used cd C:. I got C:>. The working directory was \Users\Angel Medina> This means that I navigated to the base level of my C: drive. There is no error.
#3 I used C:\Users\Angel Medina>. I got an error because the cd command is used to change directories, and hosts is a file, not a directory. So, even if you try to cd into the correct path for the hosts file on Windows, you'd still get an error because you can't change directory to a file.

#4 After using Powershell, I got a list of the contents of the directories. C:\Users\Angel Medina> was the directory ls executed with no arguments will list the files and directories in the current working directory. This is not an error! 
#5 No, the output is not an error. It's a display of some of the contents of the /etc directory. If there were an error, it might be due to the directory not existing or the user not having permission to view its contents, so the output indicates a successful listing of files and directories. I did have an error, so I need to check it out :C:\Users\Angel Medina> 
#6 This will work with any directory and will list Lists /etc/hosts specifically requests a listing of the file /etc/hosts. The output /etc/hosts confirms the existence of that file in the system However, I still got an error on my windows computer. I used C:\Users\Angel Medina> This command should work in all of the directories 
#7 The command $ cat is typically used in UNIX systems to display the content of files, but when executed without arguments, it reads input from the standard input. I used C:\Users\Angel Medina> and I got an error since the directory can't be found 

#8 $ cat /etc will also produce an error. More specifically, Error - "Is a directory" However, all directories should be able to work this command. cat is designed to display the content of files, not directories. When
/etc is specified, you are referencing a directory, not a file. 

#9 This command should display all of file content. However, I get an error, so I need to fix it. The file /etc/hosts is a system configuration file that maps hostnames to IP addresses. In the output, 127.0.0.1 is an IP address referring to the local machine, and it is mapped to the hostname localhost.
