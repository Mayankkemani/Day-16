# 🚀 Day 16 – Git & GitHub (Advanced)

## 📖 Overview

Today I completed the advanced concepts of Git & GitHub. I learned how developers collaborate using branches, merge code, resolve conflicts, manage commit history, and safely handle project versions. 

---

# 📚 Topics Covered

## 🌿 Git Branching

* Create Branch
* Switch Branch
* List Branches
* Delete Branch

### Commands

```bash
git branch
git branch feature-login
git switch feature-login
git switch -c feature-login
git branch -d feature-login
```

---

## 🔀 Git Merge

Merged changes from a feature branch into the main branch.

### Commands

```bash
git switch main
git merge feature-login
git push origin main
```

---

## ⚠️ Merge Conflict

Learned how merge conflicts occur when the same file is modified in different branches and how to resolve them manually.

### Conflict Example

```text
<<<<<<< HEAD
Hello from main
=======
Hello from feature branch
>>>>>>> feature-login
```

After resolving the conflict:

```bash
git add README.md
git commit -m "Resolved merge conflict"
```

---

## 📜 Git Log

Viewed commit history.

### Commands

```bash
git log
git log --oneline
git log --oneline --graph
```

---

## ⏪ Git Reset

Learned how to undo commits.

### Commands

```bash
git reset --soft HEAD~1
git reset --hard HEAD~1
```

---

## ↩️ Git Revert

Safely reverted a commit by creating a new reverse commit.

### Command

```bash
git revert HEAD
```

---

## 📦 Git Stash

Temporarily saved uncommitted changes.

### Commands

```bash
git stash
git stash list
git stash pop
```

---

## 🏷 Git Tags

Created version tags for releases.

### Commands

```bash
git tag v1.0
git push origin v1.0
```

---

## 🚫 .gitignore

Ignored unnecessary files and folders.

Example:

```text
node_modules/
.env
*.log
__pycache__/
```

---

## 🌍 Remote Repository

### Commands

```bash
git remote -v
git fetch
git pull origin main
git push origin main
```

---

# 💡 Key Concepts Learned

* Branching for feature development
* Merge branches into main
* Resolve merge conflicts
* Track commit history
* Undo changes using Reset & Revert
* Save temporary work with Stash
* Create project versions using Tags
* Ignore unnecessary files using .gitignore
* Fetch, Pull and Push changes to GitHub

---

# 🎯 Outcome

By completing Day 16, I gained a solid understanding of advanced Git & GitHub workflows used in professional software development and DevOps environments.

---

## 🔥 Next Step

➡️ Day 17 – Docker Fundamentals

* Docker Installation
* Images
* Containers
* Dockerfile
* Docker Hub
* Running Applications in Containers

#DevOps #Git #GitHub #VersionControl #Linux #CloudComputing #Automation #LearningInPublic
