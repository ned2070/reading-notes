# THE CODER'S COMPUTER

### The Text Editor

A **text editor** is a program used to create and edit text files.

A text editor is thus generally required for the creation and editing of code.

Notepad on Windows is an example of a basic text editor. More powerful text editors can provide many useful features to make coding easier. Examples include:

+ **Syntax Highlighting**. The editor can recognise code elements and display them in different colours, greatly aiding readability.
+ **Code Completion**. It can recognise the *start* of a code element and make it quicker to type in.
+ **Themes**. The editor's appearance can be altered to make it more pleasing to the user's eye. This can help to lessen eyestrain and fatigue when coder's spend a working day looking at a screen.
+ **Extensions**. New features can be added.

There is no "best" text editor, it's a matter of personal preference.

[More about text editors](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)

### The Command Line

The **command line**, **Command Line Interface**, **CLI** or **terminal** all refer to a text-based interface to the operating system. Most computer users work with a GUI or Graphical User Interface. The GUI is easy to use and makes unrecoverable errors more difficult. The command line is powerful and flexible, sometimes providing options unavailabe on the GUI, but it carries an assumption of the user's competence which is not always warranted!

The command line is usually accessed via a window in the GUI.

Instructions to the operating system are given on the command line as a typed in *command*. These may also be *arguments*, which are values used by the command and *flags*, which modify the operation of a command. The *shell* interprets the instructions.

[More about the command line](https://ryanstutorials.net/linuxtutorial/commandline.php)

The exact commands can vary with the shell but below are some common examples from linux.

+ **pwd** (print working directory) shows what *directory* the user is currently in.
+ **ls** (list) lists the contents of the current directory.
+ **ls projects/new-project** lists the contents of the new-project directory if it exists along this *path* i.e. there is a projects directory in the current directory and a new-project directory in the projects directory. "projects/new-project" is an example of an argument.
+ **cd** (change directory) will place the user in their home directory.
+ **cd projects** will place the user in the projects directory (if there is a projects directory in the current directory, or in other words projects is a *subdirectory* of the working directory.
+ **cd ..** moves the working directory to the one above the current one.
+ **mkdir** (make directory) is the command to make a new directory bit without an argument (the name of the new directory) will do nothing
+ **mkdir new-project** will create a directory called new-project in the current directory.
+ **touch** without an argument will do nothing.
+ **touch new-project/newfile.md** will create a new, empty file called newfile.md in the new-project subdirectory unless this file already exists. In that case it will change the file's *timestamps*, the date and time of the last file opening or modification, but without opening or changing the file.

[More about paths](https://ryanstutorials.net/linuxtutorial/navigation.php)

[More about files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

---
