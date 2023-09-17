# REVISIONS AND THE CLOUD

### What is Git?

**Git** is a *Distributed Version Control System*.



### What is Version Control?

Version Control is a system that allows you to record, track compare and revert changes in a file or set of files. The files and change records are called a **repository**.

**Distributed** means that Git allows the creation of multiple *mirrored* repositories, i.e. the repos are copies of one another, to guard against the potential failure of a single *centralised* or *local* database of changes. The repository can be thus be stored in the **cloud**.

**Cloning** is the process of copying a repo to a mirrored repository.


### Cloning from Github

If needed create a new repo in the Repositories view.

In the repo go to the green **code** button in the Code view.

In the Local tab use the button at the end of the filename to create a copy of the repo.

Preferably you have previously set up SSH with your current system.

Copy the filename.

### Using Git


Clone the repo using the **git clone** command:

git clone *filename*


Track and stage files with the **git add** command:

git add .

will track every file in the directory and stage them ready for copying.


To check the status of tracked files, use **git status**:

git status

This is optional.


To take a snapshot of changed files use the **git commit** command:

git commit -m "*your message*"

where the -m tag stores your message to report status at Github


To send changes to Github use the **git push** commaand:

git push


The workflow is thus:

+ **git add .**
+ **git commit -m "your message"**
+ **git push**




[A Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)


---