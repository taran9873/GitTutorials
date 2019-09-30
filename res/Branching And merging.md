**note:**

	when we are working on a large piece of code , it isn't recommended to make changes to main code
	so... to resolve this issue, what we do is , we simply make a branch and do our work and later when we have completed our work
	and we are ready to add it to our master branch then we simply merge it

# Creating Branches, Merging to master, Deleting branch

## step 1:
To make a new branch we simply write `"git branch "branchName" "`
this will make a branch for us.

we have successfully made branch but we are still in master branch 
so ... to make changes in that branch , we first need to switch to that branch
so for that we simply type  `git checkout "branchName"`
now we will see a msg stating `switched to "branchName"`

now we can do work
.....

~~ working ~~

....
...
....

## Ready to merge to master branch

to merge a branch to master we need to be in master to do so... if you are not in master then you can't merge
so to come back to master branch type "git checkout master"

## now merge our branch to master

`git merge branchName`

now if we no more need that branch
we can delete that branch simply by typing 

`git branch -d "branchName" `   --> this deletes only on local machine

if we want to delete branch from remote repo type this

`git push origin --delete branchName`


hope u understood branching and merging if not go through above text again


best of luck