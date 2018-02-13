## Move around the pi terminal




In the terminal, first you see $. This is called a shell prompt. It appears when the terminal is ready to accept a command.
When you type ls, the command line looks at the folder you are in, and then "lists" the files and folders inside it. The directories 2014, 2015, and the file hardware.txt are the contents of the current directory.
ls is an example of a command, a directive to the computer to perform a specific task.
When using the command line, we refer to folders as directories. Files and directories on your computer are organized into a filesystem.
Filesystem
A filesystem organizes a computer's files and directories into a tree structure:
Image of File System and File Manager

The first directory in the filesystem is the root directory. It is the parent of all other directories and files in the filesystem.
Each parent directory can contain more child directories and files. Here blog/ is the parent of 2014/, 2015/, and hardware.txt.
Each directory can contain more files and child directories. The parent-child relationship continues as long as directories and files are nested.

pwd stands for "print working directory". It outputs the name of the directory you are currently in, called the working directory.

Here the working directory is blog/. In Codecademy courses, your working directory is usually inside the home/ccuser/workspace/ directory.

Together with ls, the pwd command is useful to show where you are in the filesystem.


cd stands for "change directory". Just as you would click on a folder in Windows Explorer or Finder, cd switches you into the directory you specify. In other words, cd changes the working directory.
The directory we change into is 2015. When a file, directory or program is passed into a command, it is called an argument. Here the 2015 directory is an argument for the cd command.
The cd command takes a directory name as an argument, and switches into that directory.
To navigate directly to a directory, use cd with the directory's path as an argument. Here, cd jan/memory/ command navigates directly to the jan/memory directory.
To move up one directory, use cd ... Here, cd .. navigates up from jan/memory/ to jan/.


+ Navigate to the Y

In the terminal, after the $ type:

ls
and press Enter. Be sure to type the letter l as in "lemon" and not the number 1.

You should see three items print out below the command. Click Next to learn how this command works.

ls
pwd
cd
cd
cd ..
