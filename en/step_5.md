## Catch your first ghost

Create a quarantine directory in your `home` directory.

--- task ---
Type `mkdir quarantine/` and press <kbd>Enter</kbd>.
```
mkdir quarantine/
```

`mkdir` stands for 'make directory'. 

The `ls` command checks that directory exists:

![MKDIR Command](images/mkdircommand.png)
--- /task ---

--- task ---

Navigate into the `Documents` directory.

```
cd Documents
```

--- /task ---

--- task ---

List all the files and directories in the `Documents` directory using the commands you learned in the last step.

```
ls
```

--- /task ---

--- task ---

Do you see anything that should not be there?

--- collapse ---
---
title: Click here when you've found your first ghost!
---
That strange file named `sp00ky.txt` is the first ghost!

You've found Spooky!
![Spooky Ghost](images/ghostspooky.png)

You might have noticed that instead of being called `spooky.txt`, the virus is called `sp00ky.txt`. Hackers, both ethical and not so ethical, replace certain letters with numbers so they cannot be picked up in simple keyword searches. Keep that in mind when you are looking for the other ghosts.
--- /collapse ---
--- /task ---

### Copying files

--- task ---
Copy the ghost and put it in the quarantine directory by typing:
```
cp sp00ky.txt ~/quarantine/
```
`cp` (for 'copy') is followed by the name of the file you want to copy and then the directory you want it copied into. Here, we copied the file `sp00ky.txt` and placed it in the `quarantine` directory in the `home` directory (`~`).
--- /task ---

### Removing files

--- task ---
Now remove the ghost by typing:
```
rm sp00ky.txt
```
`rm` stands for 'remove' and deletes files (or directories).
--- /task ---

**Note:** be careful with using `rm` — it deletes things from your computer permanently! There isn't an 'undelete' command, so once you delete something with `rm`, it's gone forever. This is why we copied the file into a new directory before removing it.
