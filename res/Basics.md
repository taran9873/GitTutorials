## Basic Git commands

`git init`:
This command initialise a empty git repository in that folder i.e to keep 
track of our files , git makes a hidden folder and in which it stores
and keeps track of our file .

`git status`:
it tells about staged and unstaged changes in the local system
**In git there are three areas:**

	  `unstaged area`      ->      `staged area`         ->  `remote repository`
 (unsaved and untracked by git)    (saved and tracked by git)        (GitHub)

`git add 'file name'`:

This will move your particular file from unstaged(untracked by git) region to staged region
hmm!!! i want to add 3 files to staged area, then?

`git add 'file1' 'file2' file3'` isn't it difficult to write a lot!!!

`git add .` : if we want to add all files to staged region we need to write all file names
so... what we do is we just write git add "." and it does the work for us

`git commit -m "your msg goes here"`:

whenever you add files to staged area from unstaged region , you can write a msg associated
with that so that whenever you get around , you can remember it as reference

`git log`: it lists all the commits and changes made so far