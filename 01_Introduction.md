#### Setting Up Git
```
Windows: Download and install from git-scm.com.
Mac: Use Homebrew: brew installs git.
Linux: Use your package manager, e.g., sudo apt-get install git.
```

##### Configuration
```
git config --global user.name "Your Name" <br>
git config --global user.email "your.email@example.com"
```
##### Check Configuration
```
  git config --list
```
#### Basic Git Commands

1) Initialize a Repository
```
  git init
```
2) Clone a Repository
```
  git clone repo-url
```
3) Check status
```
  git status
```
4) Add Files to the Staging Area
```
  git add filename        (Adds specific file)
  git add .               (Adds all changes)
```
5) Commit Changes
```
  git commit -m "Commit message"
```
6) View Commit History
```
  git log
```
7) Create a New Branch
```
  git branch mynewbranch
```
8) Switch branches
```
  git checkout mybranch
```
9) Merge Branches
```
  git checkout main
  git merge mybranch
```
10) Push Changes to Remote
```
  git push origin mybranch
```
11) Pull Changes from the Remote
```
  git pull origin mybranch
```
#### Git Common Workflow

1) Clone Repository
```
  git clone <repo-url>
```
2) Create and Switch to a New Branch
```
  git checkout -b feature-branch
```
3) Work on Your Code
```
  git add .
  git commit -m "Update README.md file"
```
4) Push Changes to Remote
```
  git push origin feature-branch
```
5) Create a Pull Request on Github
```
  Go to your repository on Github
  Create a new pull request from your feature branch to the main branch
  Describe your changes and request a review
```
6) Merge Pull Request
```
  After review, merge the pull request into the main branch
```

#### Best Practices

1) Commit Often: Regular commits help you track progress and isolate changes.
2) Use Meaningful Commit Messages: Describe what changes were made and why.
3) Keep Branches Small and Focused: Work on one feature or bug fix per branch.
4) Regularly Pull Updates: Keep your local branch up to date with the remote main branch to avoid conflicts.
5) Resolve Conflicts Early: Handle merge conflicts as soon as they arise to avoid complexity.
6) Use .gitignore: Exclude files that don't need to be tracked (e.g., compiled binaries, sensitive data).
```
.gitignore Example

# Ignore node_modules directory
node_modules/

# Ignore all .log files
*.log

# Ignore specific file
secret.txt
```





