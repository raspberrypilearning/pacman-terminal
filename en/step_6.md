## Catch and quarantine ghosts

In this step, you will create a quarantine folder to put your ghosts in. You will then catch all of the ghosts and quarantine them so that they stop ghosting around and harming your computer.

A **quarantine folder** isolates infected files on a computer's hard disk. Quarantine folders are usually made automatically through Antivirus software, and although they usually have additional programming attached to them, you will simulate what it is like to create one. You can also also use what you learn here to create your own directories in your filesystem!

+ After the shell prompt, create a quarantine folder by typing `mkdir quarantine/` and pressing enter.

`mkdir` stands for "make directory".

Here we used `mkdir` to create a new directory called `quarantine/` inside the `pi/` directory. In the image, you can see that I have also checked my directory is there by using the `ls` command:

![MKDIR Command](images/mkdircommand.png)





touch ???
The touch command creates a new file inside the working directory. It takes in a filename as an argument, and then creates an empty file in the current working directory.

Here we used touch to create a new file named keyboard.txt inside the 2014/dec/ directory.

cp file?
The cp command copies files or directories. Here, we copy the contents of frida.txt into lincoln.txt.

cp file to directory
To copy a file into a directory, use cp with the source file as the first argument and the destination directory as the second argument. Here, we copy the file biopic/cleopatra.txt and place it in the historical/ directory.


mv
The mv command moves files. It's similar to cp in its usage.

mv superman.txt superhero/
To move a file into a directory, use mv with the source file as the first argument and the destination directory as the second argument. Here we move superman.txt into superhero/.

mv wonderwoman.txt batman.txt superhero/
To move multiple files into a directory, use mv with a list of source files as the first arguments, and the destination directory as the last argument. Here, we move wonderwoman.txt and batman.txt into superhero/.

mv batman.txt spiderman.txt
To rename a file, use mv with the old file as the first argument and the new file as the second argument. By moving batman.txt into spiderman.txt, we rename the file as spiderman.txt.


rm
rm waterboy.txt
The rm command deletes files and directories. Here we remove the file waterboy.txt from the filesystem.

rm -r comedy
The -r is an option that modifies the behavior of the rm command. The -r stands for "recursive," and it's used to delete a directory and all of its child directories.

Be careful when you use rm! It deletes files and directories permanently. There isn't an undelete command, so once you delete a file or directory with rm, it's gone.
