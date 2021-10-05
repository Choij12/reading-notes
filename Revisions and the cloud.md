# Revisions and the Cloud

# Git
- Git is a distrubted version control system
- stores data in a file system
- made up of snapshots
- relies on local operations and eliminates the process of retrieving data from the server
- tracks all changes, able to detect file corruption or lost data
- main states the files are in:
-   1. commited - securly stored
-   2. modified - changed but not committed
-   3. staged - changed version is flagged to be in the next snapshot

## History of Git
- rooted from the software project Linux kernel. 
- 2005
- most utilized VCS in the world

# Setting up Git Repository
- switch to the focus of the project's directory - `cd test`
- git init command - `git init`
- once to start tracking - `git add *.c` then `git add LICENSE` then `git commit -m"message"`

## Cloning
- transfer an existing Git repository from a particular server by - `git clone "link"`
- to clone a repository into a directory with a different name, - `git clone "link"test my directory`

# Local Repository Structure and Saving Changes
- 3 components:
-   1. working directory
-   2. index
-   3. head
- Saving changes - tracked & untracked

# Checking the Status, Tracking and Staging, Commenting a file, Committing all Changes, Pushing Changes
- Check the status of the files: `git status`
- for a single file - `git add "filename"` Multiple or all files - `git add *`
- to commit - `git commit -m "comment on the change"`
- to commit on all changes - `git comit -a`
- to push changes - `git push orgin master`
