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
- remote - A reference to a GIT repository. wich usually defilt to being o'origin" name.
- branch - Is like a separated version of your code that you can work on independently  at the same time.
- merge - means make two pieces of code and transform into one.

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

- `push [remote-name] [branch-name]` = put all commited files into cloud.
- `remote` - return all storaged remotes.
    - `remote add [remote-name] [git -repository-url]` - Add a git repository reference by name.
    - `remote remove [remote-name]` - removes all storaged remotes.
    - `remote get-url [remote-name]` - Get the selected remote URL
     - `remote set-url [remote-name] [git-repository-url]` - Set the selected remote URL
- `branch` - Return all storaged branchs.
    - `branch -M [other-branch-name]` - Rename current branch to other.
- `checkout`Is like git restore, returns the files to be checkout.
    - `checkout [file-name]` - restore the file to the lastest older version.
    - `checkout [path]` - restore all files from path to the latest older version
    -`checkout [branch-name]` - switch the branch to other.
    - `checkout -b [branch-name]` - Create a new branch from current one.
- `pull [remote-name] [branch-name]` - update the current branch  getting all content from target-branch and merge into current branch.
- `stash`- Store the staged files into memory
    - `stash apply` - apply all changes from last stashed changes into current branch.
- `clone [git-repository-url]` - clone the git repository into your machine in current terminal path.