# Task-7-Git-Commands-Cheat-Sheet

# GIT CHEAT SHEET

### Configuration
1. `git config --global user.name "Your Name"` - Sets the name you want attached to your commit transactions.
2. `git config --global user.email "your.email@example.com"` - Sets the email you want attached to your commit transactions.

### Repository Setup
3. `git init` - Initializes a new Git repository in the current directory.
4. `git clone <repository_url>` - Creates a copy of an existing Git repository from a specified URL.

### Staging and Committing Changes
5. `git add <file>` - Stages a specific file to be committed in the next commit.
6. `git add .` - Stages all changes (new, modified, deleted files) in the current directory for the next commit.
7. `git commit -m "Commit message"` - Commits the staged changes to the repository with a brief commit message.

### Checking Status and Differences
8. `git status` - Displays the state of the working directory and the staging area.
9. `git diff` - Shows the differences between the working directory and the staging area.
10. `git diff --staged` - Shows the differences between the staging area and the last commit.
11. `git log` - Displays the commit history for the current branch.

### Branching and Merging
12. `git branch` - Lists all the branches in the repository.
13. `git branch <branch_name>` - Creates a new branch with the specified name.
14. `git checkout <branch_name>` - Switches to the specified branch.
15. `git checkout -b <new_branch_name>` - Creates and switches to a new branch with the specified name.
16. `git branch -d <branch_name>` - Deletes the specified branch.
17. `git merge <branch_name>` - Merges the specified branch into the current branch.

### Remote Repositories
18. `git remote add origin <repository_url>` - Adds a remote repository with the specified URL and assigns it the name 'origin'.
19. `git remote -v` - Lists all remote repositories and their URLs.
20. `git push origin <branch_name>` - Pushes the commits from the local branch to the remote repository.
21. `git pull origin <branch_name>` - Fetches and merges changes from the remote repository into the current branch.
22. `git fetch origin` - Fetches changes from the remote repository but does not merge them.

### Advanced Commands
23. `git rebase <branch_name>` - Applies commits from the current branch on top of another branch.
24. `git reset <file>` - Unstages a file from the staging area but preserves its changes in the working directory.
25. `git reset --hard <commit>` - Resets the working directory, staging area, and current branch to a specified commit, discarding all changes.
26. `git push origin <tag_name>` - Pushes the specified tag to the remote repository.
27. `git rm <filename>` - Removes the specified file from the working directory and stages the removal.
