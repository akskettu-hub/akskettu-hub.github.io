---
layout: default
---

## Introduction


## Week 1: Introduction to Command Line Enviroments
The first week began by installing a command-line enviroment. In my case I used Ubuntu through WLS2, as I am a windows user. We then proceeded to familiarise ourselves with the basics of interacting with the command line. This included basic commands, such as:




| Command       | Description                        |
| ------------- | ---------------------------------- |
| `wget <URL>`  | Download a file from URL           |
| `ls`          | List contents of current directory |
| `pwd`         | Prints Current directory           |
| `whoami`      | Print current user                 |
| `mv`          | Move or rename file                | 
| `cat`         | Concatenate and print |
| `less` | Display file contents one page at a time|
| `cp` | Copy file to destination |
| `rm` | Remove file or directory |
| `mkdir` | Create directory |
| `cd` | Change working directory |

We then learned about quitting applications, which, deppending on the context, can be done with `Ctrl-d`, `Ctrl-c`, `Ctrl-x`, or `ESC`. Unfortunately, there is no universal way to quit applications and each one can potentially have their own. 

We then learned about text editors, like nano, and learned about the difference between text files and binary files. 

Beign a basic introcution to the command line, all of this week's information was useful to me in completing this course. By far the most useful part was discovering that I can use Linux on my Windows computer. I had previously tried to use PowerShell for some things, but that had proven somewhat too clunky to use regularly. Having WSL on my computer will, and indeed has, proven to be extremely useful. 



## Week 2: Navigating a UNIX system

The material for week 2 concerned the details of using the UNIX system. This included:

- Directories
	- Creating directories using `mkdir`
	- Deleting directories and their contents using `rm -R`
	- Copying directories using `cp -R`
	- Moving directories using `mv`
- UNIX file system 
	- The top most directory is called the root directory
		- The root directory's path is `/`
		- All other directories are sub-directories of the root directory
			- For example, all user home directories are contained in `/Users/`
			- `/bin/` contains essential user command binaries, such as the commands listed under Week 1
	- The `which` is used to locate the directory of a given command
	- The UNIX file system limits permissions for each file and directory. Permissions for reading, writing, and executing files can be individually configured for each user, group, and global user. 
		- These permissions can be managed using the command `chmod`.


We then went over how processes work. Running a command or programme starts a process. The operating system gives each program a process id for the purposes of keeping track of it. The command `top` can be used to see all processes currently running. By default, processes run in the forground, meaning once a process is started from the command line, the system will complete that process until a new command can be run. A process that is running in the foreground can be stoped using `Ctrl-C`. The command `ps aux` lists all currently running processes and their process ids. A process can be killed using the command `kill -9 <pid>`.

We then went over connecting to a remote server using `ssh` and securely copying onto one using `scp`. We also went over the basics of how to work on remote servers using the command line.

The material for this week was a good introduction to fundamental aspects of working in a UNIX system, and have proven to be very useful. I have not had cause yet to, for example, kill a process, but it is nevertheless valuable information for the future.

## Week 3: Basic Corpus Processing


## Week 4: Advanced Corpus Processing


## Week 5: Scripting and Configuration Files


## Week 6: Installing and Running Programs


## Week 7: Version Control
