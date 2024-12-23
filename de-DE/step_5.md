## Catch your first ghost

Create a quarantine directory in your `home` directory.

\--- task \---

Type `mkdir quarantine/` and press <kbd>Enter</kbd>.

    mkdir quarantine/
    

`mkdir` steht für 'make directory' (englisch für 'erstelle Verzeichnis').

The `ls` command checks that directory exists:

![MKDIR Befehl](images/mkdircommand.png)

\--- /task \---

\--- task \---

Navigate into the `Documents` directory.

    cd Documents
    

\--- /task \---

\--- task \---

List all the files and directories in the `Documents` directory using the commands you learned in the last step.

    ls
    

\--- /task \---

\--- task \---

Do you see anything that should not be there?

## \--- collapse \---

## title: Klicke hier, wenn du deinen ersten Geist gefunden hast!

That strange file named `sp00ky.txt` is the first ghost!

Du hast Spooky gefunden! ![Der Geist Spooky](images/ghostspooky.png)

Vielleicht hast du bemerkt, dass der Virus `sp00ky.txt` genannt wurde, statt `spooky.txt`. Sowohl ethisch korrekte als auch nicht ganz so ethische Hacker ersetzen bestimmte Buchstaben durch Zahlen, sodass sie bei der einfachen Suche nach Stichwörtern nicht so leicht gefunden werden können. Denke daran, wenn du nach den anderen Geistern suchst.

\--- /collapse \---

\--- /task \---

### Dateien kopieren

\--- task \---

Copy the ghost and put it in the quarantine directory by typing:

    cp sp00ky.txt ~/quarantine/
    

`cp` (für 'copy', englisch für "kopiere") wird gefolgt vom Namen der zu kopierenden Datei und dem Verzeichnis, in das sie kopiert werden soll. Here, we copied the file `sp00ky.txt` and placed it in the `quarantine` directory in the `home` directory (`~`).

\--- /task \---

### Dateien entfernen

\--- task \---

Now remove the ghost by typing:

    rm sp00ky.txt
    

`rm` stands for 'remove' and deletes files (or directories).

\--- /task \---

**Hinweis:** Sei vorsichtig bei der Verwendung von `rm`. Damit werden Dinge dauerhaft von deinem Computer gelöscht! Es gibt keinen Befehl, der das Löschen rückgängig macht, wenn du also etwas mit `rm` löschst, ist es für immer verschwunden. Aus diesem Grund haben wir die Datei in ein neues Verzeichnis kopiert, bevor wir sie gelöscht haben.