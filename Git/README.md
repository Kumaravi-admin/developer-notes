# Git Notes [View PDF](https://github.com/Kumaravi-admin/developer-notes/blob/main/Git/Git-notes.pdf)

A comprehensive beginner-to-intermediate Git reference covering core concepts, daily workflows, branching strategies, remote repositories, and advanced Git operations.

> **Note:** For a better reading experience and improved visual formatting, download and view the PDF version of these notes.

## Topics Covered

### 1. Introduction & Installation

- What is Git
- Version Control Systems (VCS)
- Git vs GitHub
- Git Installation
- Initial Configuration

### 2. Basic Git Concepts

- Repository
- Working Directory
- Staging Area
- Commit History
- Snapshots
- SHA-1 Hashes
- Git Workflow

### 3. Git Configuration

- Configure Username & Email
- View Configuration
- Edit Git Configurations

### 4. Starting a Project

- `git init`
- `git clone`

### 5. Basic Snapshotting

- `git status`
- `git add`

### 6. Tracking Changes

- `git diff`
- `git commit`

### 7. Undoing Changes

- `git restore`
- `git reset`

### 8. Managing Files

- `git rm`
- `git mv`

### 9. Branching & Merging

- What is a Branch
- `git branch`
- `git switch`
- `git merge`
- Merge Conflicts
- `git stash`

### 10. History & Releases

- `git log`
- `git tag`

### 11. Remote Repositories

- `git remote`
- `git push`
- `git pull`
- `git fetch`

### 12. Advanced Inspection

- Compare Branches and Commits
- `git show`

### 13. Advanced Undoing

- `git revert`
- `git rebase`
- `git cherry-pick`

### 14. Ignore Files

- `.gitignore`

### 15. Daily Workflows

- Local Development Workflow
- GitHub Workflow
- Team Collaboration Workflow

---

## Quick Start

### Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Create a New Repository

```bash
git init
```

### Clone an Existing Repository

```bash
git clone https://github.com/user/repo.git
```

### Basic Workflow

```bash
git status
git add .
git commit -m "Initial commit"
```

### Push to GitHub

```bash
git remote add origin https://github.com/user/repo.git
git push -u origin main
```

---

## Branch Workflow

Create a branch:

```bash
git switch -c feature-login
```

Switch branches:

```bash
git switch main
```

Merge branch:

```bash
git merge feature-login
```

Delete branch:

```bash
git branch -d feature-login
```

---

## Useful Commands

| Command                   | Purpose                          |
| ------------------------- | -------------------------------- |
| `git status`              | Check repository status          |
| `git add .`               | Stage all changes                |
| `git commit -m "msg"`     | Create a commit                  |
| `git log --oneline`       | View commit history              |
| `git diff`                | Compare changes                  |
| `git restore file.txt`    | Discard local changes            |
| `git reset --soft HEAD~1` | Undo last commit                 |
| `git stash`               | Save unfinished work             |
| `git pull`                | Download and merge changes       |
| `git push`                | Upload changes                   |
| `git fetch`               | Download changes without merging |

---

## Repository Structure

```text
Git Notes
│
├── Introduction & Installation
├── Basic Git Concepts
├── Configuration
├── Starting a Project
├── Snapshotting
├── Branching & Merging
├── Remote Repositories
├── Inspection Tools
├── Undoing Changes
├── Ignore Files
└── Daily Workflows
```

---

## Learning Path

Recommended order:

1. Introduction & Installation
2. Basic Git Concepts
3. Starting a Project
4. Snapshotting Commands
5. Branching & Merging
6. Remote Repositories
7. Advanced Inspection
8. Undoing Operations
9. Daily Workflows

---

## Intended Audience

- Beginners learning Git
- Students preparing for technical interviews
- Developers using GitHub
- Teams collaborating on software projects
- Anyone looking for a quick Git reference

---

## License

This repository is intended for educational purposes and personal learning.
