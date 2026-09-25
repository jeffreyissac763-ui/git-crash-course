# Git Crash Course — Git, GitHub & GitLab

A hands-on Git version control course completed through practical exercises, real-world workflows, branching strategies, collaboration workflows, recovery techniques, and CI/CD.

This repository contains the practical work completed while learning and applying Git, GitHub, and GitLab from fundamentals through professional workflows.

---

## 🎯 Course Goals

* Understand Git version control fundamentals
* Learn the Git repository architecture
* Work confidently with commits and branches
* Practice merging and conflict resolution
* Understand different methods of undoing changes
* Work with GitHub and GitLab remotes
* Practice Pull Request and Merge Request workflows
* Use stash, rebase, and cherry-pick
* Work with tags and `.gitignore`
* Configure SSH authentication
* Recover work using `git reflog`
* Understand professional Git workflows
* Practice CI/CD with GitHub Actions and GitLab CI

---

## 🧠 Git Architecture

```text
Working Directory
        │
        │ git add
        ▼
Staging Area
        │
        │ git commit
        ▼
Local Repository
        │
        │ git push
        ▼
Remote Repository
   GitHub / GitLab
```

Git manages the version history locally, while GitHub and GitLab provide remote repository hosting and collaboration features.

---

## 📚 Topics Practiced

### Git Fundamentals

* Git vs GitHub vs GitLab
* Repository initialization
* Working directory
* Staging area
* Local repository
* Remote repository
* Commits
* `HEAD`
* Branches
* Remote repositories
* `origin`

### Core Commands

```bash
git init
git clone
git status
git add
git commit
git log
git diff
```

### Branching & Merging

```bash
git branch
git switch
git switch -c
git merge
```

Practiced:

* Feature branches
* Fast-forward merges
* Three-way merges
* Merge conflicts
* Conflict resolution

### Undo & Recovery

```bash
git revert
git reset
git reset --soft
git reset --mixed
git reset --hard
git reflog
```

Practiced safely undoing changes and recovering previous repository states.

### Remote Workflow

```bash
git remote -v
git fetch
git pull
git push
git push -u origin <branch>
```

### Stashing

```bash
git stash
git stash list
git stash pop
```

### Rebase

```bash
git rebase
```

Practiced rewriting local branch history and resolving rebase situations.

### Cherry-Pick

```bash
git cherry-pick <commit>
```

Practiced applying a specific commit from another branch.

### Tags

```bash
git tag
git tag -a v1.1.0 -m "Release version 1.1.0"
```

### `.gitignore`

Practiced excluding environment files and other files that should not be tracked.

Example:

```text
.env
.venv/
__pycache__/
*.log
```

### SSH

Configured SSH authentication for GitLab and verified the connection.

---

## 🔀 GitHub Workflow

Practiced a team-style GitHub workflow:

```text
Create Feature Branch
        ↓
Develop Feature
        ↓
Commit Changes
        ↓
Push Branch
        ↓
Create Pull Request
        ↓
Review
        ↓
Merge
        ↓
Delete Feature Branch
```

---

## 🦊 GitLab Workflow

Practiced a GitLab feature branch and Merge Request workflow:

```text
Feature Branch
      ↓
Commit
      ↓
Push
      ↓
Merge Request
      ↓
Review
      ↓
Merge
```

---

## ⚙️ CI/CD

### GitHub Actions

This repository contains a GitHub Actions workflow under:

```text
.github/
└── workflows/
    └── ci.yml
```

The workflow demonstrates a basic CI pipeline triggered by pushes to `master`.

### GitLab CI

The repository also contains:

```text
.gitlab-ci.yml
```

demonstrating GitLab CI configuration.

---

## 🧪 Practical Exercises

The repository includes practical files created during the course, including exercises involving:

* Branching
* Merging
* Remote changes
* User profiles
* Cherry-pick
* GitLab workflow
* Final project development

---

## 🚀 Final Project

### AI Tools Directory

The final practical project demonstrates a feature-development workflow using Git.

```text
AI Tools Directory

├── Chatbots
├── Code Assistants
├── Image Generation
└── Developer Tools
```

The feature was developed on a dedicated branch, pushed to GitHub, submitted through a Pull Request, reviewed, merged, and the feature branch was subsequently removed.

---

## 🏷️ Releases

Tags created during the course include:

```text
v1.0.0
v1.1.0
```

These demonstrate Git's tagging and release-versioning capabilities.

---

## 🛠️ Tools Used

* Git
* GitHub
* GitLab
* GitHub Actions
* GitLab CI
* Visual Studio Code
* PowerShell

---

## 📈 Learning Progression

```text
Git Fundamentals
       ↓
Commits & History
       ↓
Branching
       ↓
Merging
       ↓
Conflict Resolution
       ↓
Undo & Recovery
       ↓
Remote Repositories
       ↓
GitHub & GitLab
       ↓
Stash
       ↓
Rebase
       ↓
Cherry-Pick
       ↓
Tags & .gitignore
       ↓
SSH
       ↓
CI/CD
       ↓
Professional Workflow
       ↓
Final Project
```

---

## 🎓 Outcome

This repository represents a practical Git, GitHub, and GitLab learning project covering version control fundamentals through professional development workflows.

The focus throughout the course was **learning by doing**: commands were practiced directly, workflows were tested, mistakes were intentionally introduced and fixed, and GitHub/GitLab collaboration workflows were applied to a final project.

---

## 👨‍💻 Author

**Jeffrey Issac**

GitHub: [jeffreyissac763-ui](https://github.com/jeffreyissac763-ui)
