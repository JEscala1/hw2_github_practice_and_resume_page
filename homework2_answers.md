Part 1 - Github
1. What command do you use to setup a git repository inside of your folder?
-ex. git init

2. What command do you use to ask git to start tracking a file?
-git add [file]
-ex. git add README.txt

3. What command do you use to ask git to move your file from the staging area to the repository?
-git push [alias] [branch]
-ex. git push origin master

Part 1 - Github II
1. What command do you use to pull any changes from the master repository into your local repository?
-git pull

2. What command do you use to unstage a file?
-git reset [file]

3. What command do you use to change your files back to how they were after a commit?
-git reset [commit]

4. Why is it important to use -- when changing files back to a previous state?
-the double dash[--] is necessary to separate the base commands from parameters providing more specific options

5. Why might you want to reset your files back to a previous commit?
-it may be best to reset files back to a specific commit as a hot fix to a bug that was included in an update

Part 1 - Github III
1. What command do you use to create a branch?
- git branch [branch-name]

2. What command do you use to use a different branch?
-git checkout [branch-name]

3. Why would you want to use a branch other than the default master?
-the new branch may include a feature that should not be in the default master and should not affect the current master until tested to go live