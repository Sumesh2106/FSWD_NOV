# Git & GitHub Basics for Full Stack Web Development

Welcome to the Git & GitHub guide for our Full Stack Web Development course.

## Why GitHub?

GitHub helps you:

- Store and manage code online
- Track project changes
- Collaborate with teammates
- Submit assignments
- Build a professional portfolio
- Learn industry-standard workflows

---

# Git Setup (One-Time Configuration)

Configure your Git account before starting:

```bash
git config --global user.name "Your Name"
git config --global user.email "yourmail@gmail.com"
```

Verify configuration:

```bash
git config --list
```

---

# Clone a Repository

Download an existing GitHub repository to your computer.

```bash
git clone https://github.com/username/project.git
```

Example:

```bash
git clone https://github.com/fargintech/fullstack-course.git
```

---

# Check Status

View the current state of your project.

```bash
git status
```

This command shows:
- Modified files
- New files
- Deleted files
- Files waiting to be committed

---

# Add Files to Staging Area

Add a specific file:

```bash
git add index.html
```

Add all files:

```bash
git add .
```

---

# Commit Changes

Save your changes with a meaningful message.

```bash
git commit -m "Completed Assignment 1"
```

Examples:

```bash
git commit -m "Added login page"
git commit -m "Created navbar"
git commit -m "Fixed CSS layout issue"
```

---

# Push Changes to GitHub

Upload your commits to GitHub.

```bash
git push origin main
```

---

# Pull Latest Changes

Download updates from GitHub.

```bash
git pull origin main
```

Always pull before starting new work.

---

# View Commit History

Display all commits:

```bash
git log
```

Short version:

```bash
git log --oneline
```

---

# Initialize a New Git Repository

Convert a local folder into a Git project.

```bash
git init
```

---

# Connect Local Project to GitHub

Add a remote repository.

```bash
git remote add origin https://github.com/username/project.git
```

Verify remote connection:

```bash
git remote -v
```

---

# Branch Management

## Create a Branch

```bash
git branch feature-login
```

## Switch Branch

```bash
git checkout feature-login
```

## Create and Switch Together

```bash
git checkout -b feature-login
```

---

# Merge Branches

Switch to main branch:

```bash
git checkout main
```

Merge another branch:

```bash
git merge feature-login
```

---

# Delete a Branch

```bash
git branch -d feature-login
```

---

# View All Branches

```bash
git branch
```

---

# Undo Changes

Restore one file:

```bash
git restore index.html
```

Restore all files:

```bash
git restore .
```

---

# Remove a File from Git

```bash
git rm file.txt
```

Commit the removal:

```bash
git commit -m "Removed unwanted file"
```

---

# Using .gitignore

Create a file named:

```text
.gitignore
```

Example:

```text
node_modules/
.env
dist/
*.log
*``

Git will*ignore these files and folders.

-*-

# Student*Assignment Workflow

## Step 1: Cl*ne Repository

```bash
git clone https://github.com/fargintech/assignment1.git
```

## Step 2: Check Sta*us

```bash
git status
```

## Ste* 3* Add Changes

```bash
git add .
*``

## Step 4: Commit Changes

*``bash
git commit -m "Completed As*ignment*1"
```

## Step 5:*Push to GitHub

```bash
git push*origin main
```

---

# Daily Deve*oper*Workflow

Before starting work:

`*`bash*git pull origin main
```

After ma*ing*changes:

```bash
git add .
git co*mit -m "Added new feature"
git pus* origin*main
```

---

# Top 10 Git*Commands Every Student Must Know

*``bash
git*clone
git status
git add .
git com*it*-m "message"
git push
git pull*git branch
git checkout
git merge
*it log --oneline
```

---

#*Recommended Tools

##*Software

- Git
-*GitHub Account
- Visual Studio Cod**- Google Chrome
- Postman
-*MongoDB Compass

## VS Code Extens*ons

###*Live Server

Run HTML projects*instantly.

### GitHub Pull Reques*s & Issues

*anage GitHub within VS Code.

### *it*ens

View commit history and code *wnership*

### Prettier

Automatically form*t code.

### ESLint

Find JavaScri*t errors*

### Path Intellisense

Auto-comp*ete*file paths.

### Material Icon The*e

Better project icons.

### Auto*Rename Tag

Automatically*rename paired HTML tags.

---

#*VS Code Internal Browser

Open the*built-in browser:

1* Press:

```text
Ctrl +*Shift + P
```

2. Search*

```text
Simple Browser
```

3* Open:

```text
http://localhost:5500
```

This allows you to view yo*r website directly inside VS Code*while using Live Server.

---

* Industry Best*Practice

Always follow:

*``bash
git pull
git*add .
git commit -m "Meaning*ul message"
git push
```

Learning*Git*and GitHub is one of the most impo*tant*skills for becoming a professional*Full*Stack Developer.
