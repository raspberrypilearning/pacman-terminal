## Catch and quarantine ghosts

In this step, you'll create a


The mkdir command stands for "make directory". It takes in a directory name as an argument, and then creates a new directory in the current working directory.

Here we used mkdir to create a new directory named media/ inside the feb/ directory.





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
