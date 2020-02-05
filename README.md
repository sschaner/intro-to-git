# git init

- Use the command "git init" in your working directory to set up git in your working directory.

# git add

- Working Directory

* Area where all of your files and directories and changes are living all the time

- Staging Area

* Files and directories that we explicitly add to the staging area

- Git Repository

* Where all our snapshots are stored

- "git status" lists the files that are tracked and not tracked (green for tracked and red for untracked)
- "git add <filename>" moves the file from the working directory to the staging area

# git commit

- 'git commit -m "Message here"' moves files in the staging area to the git repository
- To see a hisotry of commits, use "git log"

# git add files of a certain type

- To add only html files, use the command "git add \*.html" but don't include the backslash. This is called a wildcard.

# git add all files

- To add all files to the staging area, use the command "git add ."
- To add all files and folders to the staging area, use the command "git add -A"git

# git remove files

- To remove files from the staging area, use the command "git reset HEAD <filename>"

# git ignore files

- Any files listed in the .gitignore will be ignored by git.
- Rename a file with "rm <fileToBeRenamed> <newFilename>"

# git list branches

- To list all the branches in the git repository, use the command "git branch"
- To create a new branch and switch to it, use the command "git checkout -b <branch_name>"

# git add a branch

- To switch to a branch, use the command "git checkout <branch_name>"

# git merge a branch

- If we like the new features in our new branch and want to merge it with our master branch:

* Switch to the master branch with "git checkout master"
* Merge the new branch with the master branch with "git merge <new_branch_name>"

# git remove a branch

- Recommended not to delete branches. They don't take up much space and you might need them later on.
- To remove a branch, use the command "git branch -d <branch_name>"
