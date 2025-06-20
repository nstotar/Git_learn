# 🧰 Git & GitHub Reference Guide

## 📌 What is Git?
- Git is a **version control system** used to track changes in source code.
- It allows multiple people to collaborate on a project while maintaining a full history of all changes.

## ☁️ What is GitHub?
- GitHub is a **cloud-based platform** that hosts Git repositories.
- It provides a **web interface** for Git and enables **collaboration, issue tracking, pull requests**, and more.

---

## 🗝️ Key Terms

- **Repository (repo):** Where your project/code lives.
- **Commit:** A snapshot of your changes saved to Git.
- **Push:** Sending your local commits to GitHub.
- **Pull:** Getting the latest changes from GitHub.
- **Branch:** A separate version of your code used for development.
- **Merge:** Combining changes from different branches.
- **Clone:** Copying a GitHub repository to your local machine.
- **Fork:** Creating a personal copy of someone else’s repo on GitHub.
- **Pull Request (PR):** Proposing changes to be merged into a repository.

---

## ⚙️ Basic Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
````

---

## 📁 Create or Clone a Repository

* **Clone a repo from GitHub:**

```bash
git clone https://github.com/your-username/your-repo.git
```

* **Initialize a new Git repo:**

```bash
git init
```

---

## ✍️ Making Changes

* **Stage changes:**

```bash
git add .
```

* **Commit the staged changes:**

```bash
git commit -m "Your commit message"
```

---

## 🚀 Push Changes to GitHub

* **Push to the main branch:**

```bash
git push origin main
```

* **First push or pushing a new branch:**

```bash
git push -u origin branch-name
```

---

## 🔄 Pull Latest Changes

```bash
git pull origin main
```

---

## 🌿 Branching

* **Create a new branch:**

```bash
git branch feature-branch
```

* **Switch to a branch:**

```bash
git checkout feature-branch
```

* **Create and switch in one command:**

```bash
git checkout -b feature-branch
```

---

## 🔀 Merging Branches

* **Switch to the main branch:**

```bash
git checkout main
```

* **Merge another branch into main:**

```bash
git merge feature-branch
```

---

## 📋 Checking Status and History

* **Check the current state of your repo:**

```bash
git status
```

* **View the commit history:**

```bash
git log
```

---

## ⏪ Undoing Changes

* **Undo staged changes:**

```bash
git reset
```

* **Undo the last commit but keep changes:**

```bash
git reset --soft HEAD~1
```

---

## 🛠️ Other Useful Commands

* **Check remote repositories:**

```bash
git remote -v
```

* **Add a remote repository:**

```bash
git remote add origin https://github.com/your-username/your-repo.git
```

* **Remove a file from Git tracking:**

```bash
git rm --cached filename
```

---

## ✅ Happy Coding!

This reference is a helpful starting point for anyone new to Git and GitHub. Keep this guide handy and contribute to your projects with confidence.
