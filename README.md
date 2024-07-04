#### Introduction to Git

Git is a distributed version control system that tracks source code changes during software development. It allows multiple developers to work on a project simultaneously without interfering with each other’s work.

#### Key Concepts

Repository (Repo): A storage location for your project, where Git stores the project history and configuration.
Commit: A snapshot of your project at a specific point in time.
Branch: A parallel version of your project, allowing you to work on different features or fixes simultaneously.
Merge: Combining changes from different branches into one.
Remote: A version of your project hosted on the internet or network.
Clone: A copy of a remote repository on your local machine.
Pull: Updating your local repository with changes from a remote repository.
Push: Sending your local changes to a remote repository.

#### Setting Up Git

##### Installation
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








