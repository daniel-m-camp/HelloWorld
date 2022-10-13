# git init
Create a new empty local repository.  Generally don't use this, we want to grab one from GitHub

# git clone git@github.com:daniel-m-camp/HelloWorld.git
Create a working local copy of the remote repository (make sure to use ssh instead of https)

# git status
Show status of the current directory (good to do always, it gives hints on what to do next)

# git log
Shows commit history

# git add *
Adds all files to the "staging area".  The "staging area" is the stuff that is going to get committed

# git rm \<file\>
Removes file from the staging area

# git commit -m "Commit message"
Commit the changes made in the staging area.  This does NOT impact the remote repository yet.

# git remote add origin git@github.com:daniel-m-camp/HelloWorld.git
Adds a remote repository (if you didn't already do so with clone), and names it origin

# git remote -v
Lists the currently configured remote repositories

# git push origin <branchname>
Sends your committed branch to remote server origin

# git pull origin
Fetches the remote repositories branch, and merges it with your local repository

# git branch
List all branches and your current branch

# git checkout -b \<branchname\>
Create new branch and switch to it

# git checkout \<branchname\>
Switch branches

# git branch -d \<branchname\>
Deletes branch

# git diff
Views merge conflicts
