# Git
A version manager for repsitories and files.

## How to install ?
1. Go to GIT website [here](https://git-scm.com/)
2. Downloand the latest git source release.
3. Install it.

## nomeclatures
- commit - is the version file message to be displayed into GIT timeline
- staged files - storaged files to be commited
- unstaged files - files witch need to be staged to commit
- untracked files - Files witch git not known.

## commands
__to use git commands it needs to use git prefix write the command__

- `init` -initializate a new git respository into terminal current path.
- `add` - Add the file or folder path into staged files.
    - `add -A` - Add all files from all folders.
    - `add .` - Add all files and folders from current terminal path.
- `commit` - Insert a message to all staged files.
    - `commit -m "TEXT HERE"` - Insert a simple message into commit.
-`status` - return the status from all files.
- `restore` - Restore file to latest older version.
    - `restore --staged` - Restore file to unstaged version
- `log` - Return all commits order by recent date.