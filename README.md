# Version Control Assignment

## What is Version Control?
Version control is a system that helps track changes to files over time. It allows multiple people to work on a project, keep history of changes, and revert to previous versions if needed.

---

## Difference Between Git and GitHub
- **Git** is a version control system used to track changes in code locally.
- **GitHub** is a cloud platform that hosts Git repositories and allows collaboration online.

---

## 3 GitHub Alternatives
1. GitLab  
2. Bitbucket  
3. SourceForge  

---

## Difference Between git fetch and git pull
- **git fetch**: Downloads changes from a remote repository but does not merge them.
- **git pull**: Downloads changes and automatically merges them into your current branch.

---

## What is git rebase?
Git rebase is used to move or combine a sequence of commits onto another base branch. It creates a cleaner project history.

**Command:**
```bash
git rebase main


## git cherry-pick <commit-hash>

---What is git cherry-pick?

Git cherry-pick means taking a specific commit from one branch and applying it to another branch.

Instead of merging the whole branch, you just pick one particular change you want.

👉 Example:
You fixed a bug in develop, but you only want that fix in main — you use cherry-pick.

# ✅ 5. Save, Commit Changes
```bash
git add README.md
git commit -m "Add version control explanations to README"
