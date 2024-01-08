**Git & Github**

##It is use for version controlling which keep and track our changes.

##If You have just installed git:-

-git config --global user.name "Nikhil" -git config --global user.mail "nikhilkumar18101998@gmail.com"

##git

###-->Create a empty folder

-git status:-It will tell about the status of your git.

-git init:- it converts a normal file into a repo run only one time when you intialise an repo

-git add fileName:-the filname which you want to stage or get tracked by Git

-git add .:-If you want to stage the entire change.

-git commit -m "Any relevant commit message":-It is used to saving the changes to git.

-git branch:-will let you know the current branch

-git diff --cached:-will tell you about the difference between previous and current commit.

###git log:- 
 -it is used to display the commit history of a Git repository.
 
 -When you run this command, it shows a list of commits in reverse chronological order (the most recent commits appear first)
 
 -This will show you information about each commit, including the commit hash, author, date, and commit message. -we can use git log --oneline, which displays each commit on one line.

###git checkout commitNumber:- 
-If you want to move to a specific commit in Git, you can use the git checkout command followed by the commit hash or reference. 

-when you do this, you will be in a "detached HEAD" state, meaning you won't be on any branch. 

-detached HEAD state means any changes you make won't belong to any branch. If you want to make changes based on that commit, you might want to create a new branch: 

git checkout -b newBranchName commitNumber

##Branching

-main/master is the default branch 

-we can use one branch at a time (active branch) 

-commands work on active branch. -HEAD also points to active branch.

-HEAD is a special pointer or reference that represents the latest commit in the currently checked-out branch.