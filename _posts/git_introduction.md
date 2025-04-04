---
layout: post
title: "Introduction to Git: Version Control Basics"
categories: git tutorials
---

## What is Git?
Git is a **distributed version control system** that helps developers track changes in code, collaborate with teams, and manage projects efficiently.

### Why Use Git?
- Tracks changes in source code
- Enables collaboration among developers
- Supports branching and merging
- Works both online (GitHub, GitLab, Bitbucket) and offline

## Basic Git Commands Flow

### 1️⃣ **Setup Git for First-Time Use**
Before using Git, configure your name and email:

git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"

### 2️⃣ **Initialize a Git Repository**
Start tracking a project by initializing a Git repository:

git init

###3️⃣ **Check Repository Status**
To see untracked and modified files:

git status

###4️⃣ **Add Files to Staging**
Before committing, add files to the staging area:

git add filename   # Add a specific file
git add .          # Add all modified files

###5️⃣ **Commit Changes**
Commit staged changes with a message:

git commit -m "Initial commit"

###6️⃣ **View Commit History**
To check past commits:

git log --oneline

###7️⃣ **Connect to a Remote Repository**
To push changes to GitHub or any remote:

git remote add origin https://github.com/your-username/repository.git
git push -u origin main

###8️⃣ **Pull the Latest Changes**
Sync your local repository with the remote:

git pull origin main

###9️⃣ **Create a New Branch**
For working on a new feature without affecting the main branch:

git branch feature-branch
git checkout feature-branch

###1️⃣0️⃣ **Merge Branches**
After completing changes, merge them back to main:

git checkout main
git merge feature-branch

###1️⃣1️⃣ **Push Changes to Remote**
Upload local commits to GitHub:

git push origin main
