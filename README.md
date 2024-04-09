
# Linux

- Linux is a Unix-like OS developed By Linus Torvalds and thousands of opensource contributors

- Linux is an operating system it is more reliable and secure than others; 

- Completely opensource

- 17 Sep 1991

- Linux is everywhere!

        - 85% of all Smartphones are based on Linux.

        - Car Uses Linux Especially self-driving cars

        - even refrigerators need Linux to run

        - Top 500 supercomputers run on Linux

## Why use Linux?
#### Windows

- GUI Based OS 

- PowerShell for scripting

- Need to Purchase a License 

- Requires antivirus software

- May Graffics cards support better for Gaming

#### Linux

- CLI Based OS and GUI options

- Bash and other shells for scripting

- License is free

- More secure than Windows

- Less developer focus on Gaming

#### Advantages

- Opensource

- Freely available

- Secure

- Lightweight Interface 

- Multi user Os

#### Disadvantages

- Harder Learning curve 

- Hardware drivers

- Limited Software availability 

- Poor support for Gaming

- Difficult to Troubleshoot

## GNU/Linux
GNU/Linux is a Unix-like Os made up of different OS components and services that create the Linux OS.

## Linux Distros

- Debian

- fedora

- Ubuntu

- Linux mint

- CentOS

- Red Hat

- SUSE 

- Kali Linux

## Basics of shell

A Shell interprets the commands we have entered send into the OS to perform them 

![img](https://media.geeksforgeeks.org/wp-content/uploads/20200105215737/Untitled-Diagram-215-1.jpg)

#### Top Shells in Linux

- Bash:
    The Bourne Again Shell is the default shell in a lot of Linux distributions. It is the most portable shell available.

- zsh:
    It is similar to bash or an extended version of it. It has a lot of useful features like sharing your command history across multiple terminals

- fish:
    Friendly and Interactive shell is again an extended version of the common shell. It has great features like autocompletion of commands

- tcsh:
    Tenex C shell is an extended version of the C shell. The plus of tcshis its scripting language, because it will be similar for users with experience in C programming

#### CLI

- Linux provides an interface for users

- Interact with OS

- Bridge between human-readable commands and underlying kernel

## Basics of Kernel

a Linux Kernel is a Unix Like OS Kernel. It is a computer program witch is the core interface witch connect Hardware companies to the software processes

    The kernel is a computer program that acts as the brain and centre of os

#### Top operations performed by a Kernel

- Process Management:
    `The kernel Keeps track of all active processes running on the system and it maintains a process table that conatins information about each process`

- Memory Management:
    `The kernel handles memory allocation and protection`

- Device Management:
    `The kernel interacts with hardware devices such as disks, networks interface and peripherals it provides an interface for user-level applications to communicate with these devices`

- Input/Output(I/O) Communication:
    `The kernel facilitates communication between user-level applications and hardware'

## Linux Directory Structure

|Directories|Description|
|:-----------:|:------------------------------------------:|
|/bin|essential user binaries such as the bash shell ls, cp commands|
|/boot|contain files needed to boot the system|
|/dev| It is the location of the device files such as dev/sda1, dev/sda2, etc.|
|/etc|system configuration files such as network settings, user a/c info, etc.|
|/home|user home directory. It is the default current directory|
|/Lib|system Libraries and kernel modules|
|/media|mount points for external/removable devices such as cd, DVD and USB drives.|
|/mnt|Temporary mount points|
|/opt|optional or third-party software.|
|/proc|conatinsinfo about the running processes with a specific process ID or PID|
|/root|root user home directory ie, system admin|
|/run|it stores volatile runtime data.|
|/sbin| binary executable programs for an administrator.|
|/temp|Temporary Files|
|/srv|It contains server-specific and server-related files.|
|/usr|User related programs|
|/var|log files / variable data or files that change frequently|

## Baisc commands

nithin@nithinspc2:~$:
- username:nithin
- hostname:nithinspc2
- ~: representing home directory

### Commands

|Commands|Description or example|
|:--------------:|:--------------------------------------|
|man| manual of commands|
|sudo|superuser do root level permissions|
|pwd|present working directory|
|free|display free and used memory|
|du|disk usage how much space a file or directory|
|df|disk free, use to report systom disk space|
|hostname|show or set system name or show ip|
|logname|for display logname|
|uname|basic info about the os|
|ls|list the files and folders|
|cd|To navigate b/w Directories|
|mkdir|to create Directories|
|rmkdir|to remove Directories|
|rm|remove file or directory|
|clear|clear terminals content|
|history|to see commands history|
|w|show logged users in the system also show corrent process|
|last|dispaly the list of all users logged in since 'var/log/wtmp' was created|
|alias|alias p='pwd'|
|touch|to create empty file|
|cat|to see what inside the file|
|tac|to see reverse order inside the file|
|head|to see top 10 inside file -n num of lines|
|tail|bottom 10|
|sort|sort the file content|
|echo|print text on the terminal|
|mv|Move or Rename the file|
|cp|copy fiels or Directories|
|lscpu|list cpu info|
|lsusb|usb divice list|
|lsblk|list block divicess / show all connected storage divicess|
|which|for find path of Executable file|
|whereis|view the exact location of any command|
|wget|downlaod files from internet|
|grep|serch specific string on output|
|cal|calendar|
|date|date|
|reboot|for reboot system|
|poweroff|for poweroff system|
|uptime|find how long is system active|
|ip addr show|show the address of conecting all interface of the Linux|
|ping|to check network connectivity also show the response time ping www.google.com|
|find|search file give the file path find /home /cat.png|

## Test Management commands

|Commands|Description or example|
|:--------------:|:--------------------------------------|
|cat|to see what inside the file|
|tac|to see reverse order inside the file|
|head|to see top 10 inside file -n num of lines|
|tail|bottom 10|
|sort|sort the file content|
|echo|print text on the terminal|
|find|serch file adn directory in a hirarical Structure|
|grep|serch specific string on output|
|more|read content of a file by page on page|
|less|same as more advance version doesn’t load the entire file but loads it part by part which makes it faster|
|wc|word count|

---

**'|' Pipe operator:** 

A pipe is a form of redirection (transfer of standard output to some other destination), The pipe is used to combine two or more commands, and in this, the output of one command acts as input to another command 

eg.   ls | grep file.txt 

---

---

**Globing** 
1) asterisk (*) 
\* is used to match any number of characters(zero or more), to understand more you can refer to the example taken above. 

2) question mark(?) 
? is used to match exactly one character. 

3) Square Brackets [] 
Square brackets are used to match the characters inside []
‘hello[1-5]’ will display all files and directories starting with ‘hello’, then the next character can be a number from 1 to 5. 

4) exclamation mark (!) 
! is used to exclude characters from the list that is specified within the square brackets.
ls hello[!3]
dislpay ending with eny character but not 3

