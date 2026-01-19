# learning-1
I am understood fundamental concepts till now ,trying to practice now

# Git GitHub Workflow Assignment

## Purpose
Practice Git & GitHub workflow using branches, pull requests, conflict resolution, and stash.

## Branching Strategy
- main → stable code
- feature/* → new features

## Git Commands Learned
- git clone
- git branch
- git checkout
- git commit
- git push
- git pull
- git revert
- git reset
- git stash


For conflict handling:

** Create branches feature/change-app-name and feature/change-app-version. Modify the same line in index.js,
merge both into main, and resolve conflict manually. Document cause and resolution steps

git checkout -b feature/change-app-name

Done the changes

git add src/index.js
git commit -m "Change application name in log"
git push origin feature/change-app-name


git checkout -b feature/change-app-version



## Merge Conflict Resolution

**Cause:**
- Two branches modified the same line in `src/index.js`.

**Resolution:**
- Git detected conflicting changes.
- Manually resolved by combining app name and version.
- Removed conflict markers and completed merge.
