Hello!
This is a text file with instructions.
Like a personal reference file for everything GitHub.
Proper credits to Git-It by Jlord for this tutorial.

Make a new folder (make directory):
    mkdir <FOLDERNAME>
Navigate into an existing folder (change directory):
    cd <FOLDERNAME>
List the items in a folder:
    ls

Check Git version:
    git --version
Set your name:
    git config --global user.name "<name>"
Set your email:
    git config --global user.email <email>
Set your Github account (case sensitive):
    git config --global user.username <username>

Turn Git on for a folder:
    git init
Check status of changes to a repository:
    git status
View changes to files:
    git diff
Add a file's changes to be committed:
    git add <FILENAME>
To add all files changes:
    git add .
To commit (aka save) the changes you've added:
    git commit -m "your commit message"
Copy a repository to your computer
    git clone <URL>

Create a new branch:
    git branch <BRANCHNAME>
Move onto a branch:
    git checkout <BRANCHNAME>
Create and switch branch:
    git checkout -b <BRANCHNAME>
List the branches:
    git branch
Rename a branch you're currently on:
    git branch -m <NEWBRANCHNAME>

Add remote connections:
    git remote add <REMOTENAME> <URL>
Set a URL to a remote:
    git remote set-url <REMOTENAME> <URL>
View remote connections:
    git remote -v

Pull in changes:
    git pull
Pull in changes from a remote branch:
    git pull <REMOTENAME> <REMOTEBRANCH>
See changes to the remote before you pull in:
    git fetch --dry-run

Push changes:
    git push <REMOTENAME> <BRANCHNAME>
Merge a branch into current branch:
    git merge <BRANCHNAME>

Delete a local branch:
    git branch -D <BRANCHNAME>
Delete a remote branch:
    git push <REMOTENAME> --delete <BRANCHNAME>