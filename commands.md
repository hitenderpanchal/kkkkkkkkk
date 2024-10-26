
Here’s a quick guide to essential Git commands, each with a brief explanation:

git init
Initializes a new Git repository in the current directory.

git clone <repository-url>
Creates a local copy of a remote repository.

git status
Shows the current status of the working directory and staging area.

git add <file> or git add .
Stages changes (files) for the next commit; . stages all changes in the directory.

git commit -m "commit message"
Commits the staged changes with a descriptive message.

git log
Displays the commit history of the repository.

git branch
Lists all branches in the repository. Adding <branch-name> creates a new branch.

git checkout <branch-name>
Switches to the specified branch.

git merge <branch-name>
Merges the specified branch into the current branch.

git pull
Fetches changes from the remote repository and merges them into your local branch.

git push
Uploads your local commits to the remote repository.

git remote add origin <repository-url>
Sets the remote repository URL as "origin" for easy pushing and pulling.

git stash
Temporarily saves changes that aren’t ready to commit.

git stash pop
Applies the stashed changes back to your working directory.

git reset <file>
Unstages a file that was previously added with git add.

git revert <commit-id>
Creates a new commit that undoes the changes of a previous commit without changing history.

git diff
Shows the differences between changes in your working directory and the last commit.

git rebase <branch-name>
Reapplies commits on top of another base branch, often used to update a feature branch.

git tag <tagname>
Creates a tag at the current commit, often used to mark release points.

git config --global user.name "Your Name" and git config --global user.email "you@example.com"
Sets up your Git username and email for commits.
