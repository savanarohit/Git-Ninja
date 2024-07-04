#### Git Advance 

##### Rebase

Rebase re-applies your changes onto another branch, which can create a cleaner history.
```
git checkout feature-branch
git rebase main
```
##### Stashing

Stashing allows you to temporarily save changes without committing them.
```
git stash
git stash pop   # Retrieve stashed changes
```
##### Cherry-Picking

Apply a specific commit from one branch to another.
```
git checkout main
git cherry-pick <commit-hash>
```