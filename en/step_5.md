## Catch and quarantine your first ghost

In this step, you will create a **quarantine folder** to put your ghosts in. You will then catch all of the ghosts and stick them in this folder so that they stop ghosting around and harming your computer like viruses do.

A quarantine folder isolates suspicious files so they cannot harm your computer. They are usually made automatically by antivirus software and have additional programming attached to them — you will simulate what it is like to create one.

First off, you will learn to create your own directories in your file system!

+ Next to the shell prompt, create a quarantine folder by typing `mkdir quarantine/` and pressing <kbd>Enter</kbd>.
  ```
  mkdir quarantine/
  ```

  `mkdir` stands for 'make directory'. The command you typed in created a new directory called `quarantine` inside the `pi` directory. In the image, you can see that I have also used the `ls` command to check that my directory exists:

  ![MKDIR Command](images/mkdircommand.png)


### Let's catch our first ghost!

+ Navigate into the `Documents` directory using the commands you learned in the last step.

  --- hints ---
  --- hint ---
  Type this into your terminal window:
  ```
  cd Documents/
  ```
  --- /hint ---
  --- hint ---
  If that did not work, type `cd` first to navigate into your home directory, then try `cd Documents/`.
  ```
  cd
  cd Documents/
  ```
  --- /hint ---
  --- /hints ---

+ List all the files and directories in the `Documents` directory using the commands you learned in the last step.

  --- hints ---
  --- hint ---
  Can you find out which command you should use in the drop-down information boxes above?
  --- /hint ---
  --- hint ---
  Use:
  ```
  ls
  ```
  --- /hint ---
  --- /hints ---

+ Look at the directories. Do you see anything strange that looks like it should not be there?

  --- collapse ---
  ---
  title: Click here when you've found your first ghost!
  ---
  That strange file named `sp00ky.txt` is a virus. If you've spotted it, you have found the first ghost!

  You've found Spooky!
  ![Spooky Ghost](images/ghostspooky.png)

  You might have noticed that instead of being called `spooky.txt`, the virus is called `sp00ky.txt`. Hackers, both ethical and not so ethical, replace certain letters with numbers so they cannot be picked up in simple keyword searches. Keep that in mind when you are looking for the other ghosts.
  --- /collapse ---


### Copying files

+ Copy the ghost and put it in the quarantine folder by typing:
  ```
  cp sp00ky.txt /home/pi/quarantine/
  ```
  `cp` (for 'copy') is followed by the name of the file you want to copy and then the directory you want it copied into. Here, we copied the file `sp00ky.txt` and placed it in the `quarantine` folder.


### Removing files

+ Now remove the ghost by typing:
  ```
  rm sp00ky.txt
  ```
  `rm` stands for 'remove' and deletes files (and directories). Here you have removed `sp00ky.txt` from the folder where you found it to stop it from doing damage.

  **Note:** be careful with using `rm` — it deletes things from your computer permanently! There isn't an 'undelete' command, so once you delete something with `rm`, it's gone forever. This is why we copied the file into a new directory before removing it.

You're now ready to safely catch all the ghosts!
