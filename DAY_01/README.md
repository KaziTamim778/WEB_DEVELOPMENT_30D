# DAY ONE OF 30 DAYS CODING CHALLENGE

## Todays Goal is to learn the basics of git & GitHub 

## Git Setup & Init 


```yaml
# Globally Set Your User Name
git config --global user. name "Your Name"

# Globally Set Your Email
git config --global user.email "you@example.com"

# Initialize a repo
git init 
```
## Track & Save Changes

```yaml
# Show modified/ unstaged files
git status

# Stage all changes
git add .
git commit -m "Describe what you changed "
```
## Branching Made Easy

```yaml 
# Create a new branch
git branch feature-x

# Switch to the new branch
git checkout feature-x

# Merge changes into current branch
git merge feature-x
```
## Revert or Reset Changes

```yaml
# Revert file to last commit
git restore <file>

# Unstage a file
git reset HEAD < file>

# Revert a commit with a new one
git revert <commit-id>
```
## Connect to Remote Repo
```yaml 
# Link to remote
git remote add origin <repo-url>

# Push code to main
git push -u origin main

# Pull latest from remote
git pull origin main
```