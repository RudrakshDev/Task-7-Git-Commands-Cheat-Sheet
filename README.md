# Task-7-Git-Commands-Cheat-Sheet

# GIT CHEAT SHEET

### Configuration
1. ```git config --global user.name "Your Name"``` - Sets the name you want attached to your commit transactions. <button onclick="copyToClipboard('git config --global user.name \\'Your Name\\'')">Copy</button>
2. ```git config --global user.email "your.email@example.com"``` - Sets the email you want attached to your commit transactions. <button onclick="copyToClipboard('git config --global user.email \\'your.email@example.com\\'')">Copy</button>

### Repository Setup
3. ```git init``` - Initializes a new Git repository in the current directory. <button onclick="copyToClipboard('git init')">Copy</button>
4. ```git clone <repository_url>``` - Creates a copy of an existing Git repository from a specified URL. <button onclick="copyToClipboard('git clone <repository_url>')">Copy</button>

### Staging and Committing Changes
5. ```git add <file>``` - Stages a specific file to be committed in the next commit. <button onclick="copyToClipboard('git add <file>')">Copy</button>
6. ```git add .``` - Stages all changes (new, modified, deleted files) in the current directory for the next commit. <button onclick="copyToClipboard('git add .')">Copy</button>
7. ```git commit -m "Commit message"``` - Commits the staged changes to the repository with a brief commit message. <button onclick="copyToClipboard('git commit -m \\'Commit message\\'')">Copy</button>

### Checking Status and Differences
8. ```git status``` - Displays the state of the working directory and the staging area. <button onclick="copyToClipboard('git status')">Copy</button>
9. ```git diff``` - Shows the differences between the working directory and the staging area. <button onclick="copyToClipboard('git diff')">Copy</button>
10. ```git diff --staged``` - Shows the differences between the staging area and the last commit. <button onclick="copyToClipboard('git diff --staged')">Copy</button>
11. ```git log``` - Displays the commit history for the current branch. <button onclick="copyToClipboard('git log')">Copy</button>

### Branching and Merging
12. ```git branch``` - Lists all the branches in the repository. <button onclick="copyToClipboard('git branch')">Copy</button>
13. ```git branch <branch_name>``` - Creates a new branch with the specified name. <button onclick="copyToClipboard('git branch <branch_name>')">Copy</button>
14. ```git checkout <branch_name>``` - Switches to the specified branch. <button onclick="copyToClipboard('git checkout <branch_name>')">Copy</button>
15. ```git checkout -b <new_branch_name>``` - Creates and switches to a new branch with the specified name. <button onclick="copyToClipboard('git checkout -b <new_branch_name>')">Copy</button>
16. ```git branch -d <branch_name>``` - Deletes the specified branch. <button onclick="copyToClipboard('git branch -d <branch_name>')">Copy</button>
17. ```git merge <branch_name>``` - Merges the specified branch into the current branch. <button onclick="copyToClipboard('git merge <branch_name>')">Copy</button>

### Remote Repositories
18. ```git remote add origin <repository_url>``` - Adds a remote repository with the specified URL and assigns it the name 'origin'. <button onclick="copyToClipboard('git remote add origin <repository_url>')">Copy</button>
19. ```git remote -v``` - Lists all remote repositories and their URLs. <button onclick="copyToClipboard('git remote -v')">Copy</button>
20. ```git push origin <branch_name>``` - Pushes the commits from the local branch to the remote repository. <button onclick="copyToClipboard('git push origin <branch_name>')">Copy</button>
21. ```git pull origin <branch_name>``` - Fetches and merges changes from the remote repository into the current branch. <button onclick="copyToClipboard('git pull origin <branch_name>')">Copy</button>
22. ```git fetch origin``` - Fetches changes from the remote repository but does not merge them. <button onclick="copyToClipboard('git fetch origin')">Copy</button>

### Advanced Commands
23. ```git rebase <branch_name>``` - Applies commits from the current branch on top of another branch. <button onclick="copyToClipboard('git rebase <branch_name>')">Copy</button>
24. ```git reset <file>``` - Unstages a file from the staging area but preserves its changes in the working directory. <button onclick="copyToClipboard('git reset <file>')">Copy</button>
25. ```git reset --hard <commit>``` - Resets the working directory, staging area, and current branch to a specified commit, discarding all changes. <button onclick="copyToClipboard('git reset --hard <commit>')">Copy</button>
26. ```git push origin <tag_name>``` - Pushes the specified tag to the remote repository. <button onclick="copyToClipboard('git push origin <tag_name>')">Copy</button>
27. ```git rm <filename>``` - Removes the specified file from the working directory and stages the removal. <button onclick="copyToClipboard('git rm <filename>')">Copy</button>
