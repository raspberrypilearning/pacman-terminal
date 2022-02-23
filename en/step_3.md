## Start the treasure hunt

To start the treasure hunt, you will need to download a file that will unleash the Pac-Man ghosts! Please note that **you will not download real viruses** by completing this step. The files you'll download are completely safe and cannot do any damage to your computer.

In the terminal, you can download and open files or scripts very easily using **bash**. Bash is a program that listens to your commands and does what you tell it to do. Hackers are concerned with problems in computer systems and programs, and they need to give commands to find these problems and fix them. Therefore, they need to be good at using commands in programs like bash.

--- task ---
To access bash, make sure you have opened a terminal window.

In the terminal, you will see `$`. This is called a **shell prompt**. It appears when the terminal is ready to accept a command.

![Shell Prompt](images/shellprompt.png)

Next to the `$` (the shell prompt), type or copy and paste:
```
wget -O - https://rpf.io/pacmanstart | bash
```
--- /task ---

--- task ---
Press the <kbd>Enter</kbd> key to run this line of code. You will see a lot of text appear in the terminal. This means it is downloading the files to start the treasure hunt.
  
**Note:** the `| bash` command at the end tells bash to automatically run the file after it is downloaded. Using this command is generally not very secure, because it means the downloaded files will be run without you checking them first. However, here it is the easiest way to start the treasure hunt, and it also shows you how easy it is to download viruses.
--- /task ---

--- task ---
Press <kbd>Ctrl l</kbd> to clear the terminal window.
--- /task ---

Next you'll learn how to navigate the command line so you can start finding and catching the ghosts.
