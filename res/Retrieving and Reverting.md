# Retrieving and Reverting

`git checkout "filename"`

this will delete/remove your local version file and restore
that file from remote repository(hosted on GitHub)

`git commit –amend -m “message”`

Reverts back to edit last commit, add changes or
edit commit message. This will amend to last commit, and not create a new log entry.

## Retrieving a Previous Version of File

`git checkout ‘S-H-A number of the commit you want to take it from’ – ‘filename’`

whenever you commit changes , you get a 6 char/digit unique code and that code is called S-H-A

## REMOVE UNTRACKED FILES

`git clean -n`: Lists files that are untracked and are about to be deleted

`git clean -f`: Force remove files that are in unstaged region only



