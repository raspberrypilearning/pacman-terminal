## Move around the Pi terminal

In this step, you will learn how to get Pacman to navigate the Pi's terminal, just like when Pacman moves around his maze.

![Pacman Gif](images/pacmangiphy.gif)

### Listing directory content

The `ls` command looks at the folder you are in and then lists the files and **directories** inside it (`ls` stands for 'list'). When you're using the terminal, folders are called directories.

--- task ---
After the shell prompt, type `ls` and press <kbd>Enter</kbd>. Make sure you type the letter `l` as in "lime" and not the number `1`.
```
ls
```
You should get a similar result to this:
![LS Command](images/lscommand.png)

Here, you cannot see any files, because there aren't any, but you can see lots of directories.

The directory, or folder you are in, therefore contains these directories:
  `Desktop`, `Downloads`, `Pictures`, `python_games`, `Scratch Projects`, `Videos`, `Documents`, `Music`, `Public`, `Scratch`, and `Templates`
--- /task ---


### Print working directory

`pwd` stands for 'print working directory'. This command shows where you are in the Pi's **file system**, meaning it tells you what directory you are currently in in the command line — your working directory! You can use this command at any time to not get lost.

--- task ---
Type `pwd` and press <kbd>Enter</kbd>.
```
pwd
```
This is what you should get (results in the red box):
![PWD Command](images/pwdcommand.png)

Here you can see that you are in the `/home/pi` directory. This means you're inside the `pi` directory, which itself is stored inside the `home` directory. (The `/` symbols aren't part of the directory names, the command line just uses them to show you directories.)

  The **file system** is the way files and directories on your computer are organised. A computer's file system usually has a tree structure:

  |                                              |                                              |
  | :------------------------------------------: | :------------------------------------------: |
  | ![File Manager](images/filemanager.png)      | ![File Tree](images/filetree.png)            |
--- /task ---


### Change directory

`cd` stands for 'change directory'. Just the same as you can click on a folder icon in a graphic file manager to go into it, `cd` lets you go into the directory you tell it. To get into a directory, just type the command `cd` followed by a space, and then the name of the directory and a forward slash `/`.

--- task ---
To try moving into a different directory, type `cd Documents/` and press <kbd>Enter</kbd>.
```
cd Documents/
```
![CD Documents](images/cddocuments.png)

Now you've navigated into the `Documents` directory!

The terminal tells you here that you are in `Documents`:

![CD Documents path](images/cddocumentspath.png)
--- /task ---


### Moving between directories

--- task ---
You can move up (or back, depending on how you want to imagine it) one directory in the file system by typing `cd` followed by a space and two full stops `..`, and then pressing <kbd>Enter</kbd>.
```
cd ..
```
`cd ..` navigates up from `home/pi/Documents` back to `home/pi`.

You can quickly check you're in the right directory using the `pwd` command:

![CD DotDot Command](images/cddotdotcommand.png)
--- /task ---

Now you're ready to catch your first ghost!
