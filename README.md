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
