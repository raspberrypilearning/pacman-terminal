## Catch and quarantine ghosts

In this step, you will create a quarantine folder to put your ghosts in. You will then catch all of the ghosts and quarantine them so that they stop ghosting around like viruses do and harming your computer.

A **quarantine folder** isolates suspicious files so they cannot harm your computer. They are usually made automatically through Antivirus software and have additional programming attached to them, however you will simulate what it is like to create one.

You can also also use what you learn here to create your own directories in your filesystem!

+ After the shell prompt, create a quarantine folder by typing `mkdir quarantine/` and pressing enter.
```bash
mkdir quarantine/
```

`mkdir` stands for "make directory". We used `mkdir` to create a new directory called **quarantine/** inside the **pi/** directory. In the image, you can see that I have also checked my directory exists by using `ls`:

![MKDIR Command](images/mkdircommand.png)

### We are now going to catch our first ghost!

+ Navigate into the **Documents/** directory using the commands you learned in the last step.

HINT

+ List all the files and directories in the **Documents/** directory using the commands you learned in the last step.

HINT

Do you see anything strange in the directory that looks like it should not be there?

INFO ABOUT WHY PPL USE SYMBOLS ETC AND CAN REFER BACK TO USE OF L .. IN A HINT?

### Copying Files

+ Copy the ghost and put it in the quarantine folder by typing:
```bash
cp sp00ky.txt home/pi/Documents/quarantine/
```
`cp` is followed by the name of the file to copy and then the directory you want it copied into. Here, we copied the file **sp00ky.txt** and placed it in the **quarantine/** folder.

IMAGE

### Removing Files

+ Now remove the ghost by typing:
```bash
rm sp00ky.txt
```
`rm` deletes files and directories. Here we have removed **sp00ky.txt** from the filesystem.

IMAGE

Be careful when you use rm! It deletes files and directories permanently. There isn't an undelete command, so once you delete a file or directory with rm, it's gone. This is why we copied the file into a new directory before removing it.
