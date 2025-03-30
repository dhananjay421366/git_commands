# git_commands
git init  # Initialize a new Git repository in the current directory  

git clone <repo_url>  # Clone an existing Git repository from GitHub  

git status  # Check the current status of the working directory  
git add <file>  # Add a specific file to the staging area  
git add .  # Add all changes in the working directory to the staging area  
git commit -m "message"  # Commit staged changes with a message  
git push origin <branch>  # Push local commits to a remote repository  
git pull origin <branch>  # Pull the latest changes from the remote repository  

git branch  # List all branches in the repository  
git branch <branch_name>  # Create a new branch  
git checkout <branch>  # Switch to a specific branch  
git checkout -b <branch>  # Create and switch to a new branch  
git merge <branch>  # Merge another branch into the current branch  
git branch -d <branch>  # Delete a branch locally  
git push origin --delete <branch>  # Delete a branch from the remote repository  

git reset --hard HEAD  # Reset to the last committed state, discarding all changes  
git reset --soft HEAD~1  # Undo the last commit, keeping the changes staged  
git revert <commit_id>  # Revert a specific commit  
git checkout -- <file>  # Discard changes in a specific file  

git remote -v  # Show the remote URLs linked to the repository  
git remote add origin <repo_url>  # Add a remote repository  
git fetch origin  # Fetch updates from the remote repository  
git push -u origin <branch>  # Push a new branch and track it  
git pull --rebase origin <branch>  # Pull changes with rebase instead of merge  

git log  # Show commit history  
git log --oneline  # Show a short commit history  
git diff  # Show changes between working directory and last commit  
git diff --staged  # Show changes in the staging area  

git stash  # Save uncommitted changes for later  
git stash pop  # Restore the most recent stash  
git stash list  # Show all stashes  
git stash drop  # Delete the last stash  

gh auth login  # Login to GitHub CLI  
gh repo create <name>  # Create a new GitHub repository  
gh repo clone <repo>  # Clone a repository from GitHub  
gh issue list  # List issues in a repository  
gh pr create  # Create a pull request  

git reset --soft HEAD~1  # Undo last commit but keep changes  
git push --force  # Force push (use with caution!)  
git commit --amend -m "New message"  # Fix last commit message  
git rebase -i HEAD~3  # Squash multiple commits into one  
git log --graph --oneline --all  # See commit history graphically  

git init  # Initialize a Git repo for a new project  
git add .  # Stage all files  
git commit -m "Initial commit"  # Commit initial files  
git branch -M main  # Rename branch to main  
git remote add origin <repo_url>  # Connect local repo to GitHub  
git push -u origin main  # Push initial commit to GitHub  

git checkout -b feature-branch  # Create and switch to a new feature branch  
git add .  # Stage changes  
git commit -m "Added new feature"  # Commit changes  
git push origin feature-branch  # Push feature branch to GitHub  
gh pr create  # Create a pull request from CLI  
git branch -d feature-branch  # Delete branch locally after merging  
git push origin --delete feature-branch  # Delete remote branch after merging  
