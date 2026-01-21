# Aperture Technology – Source Code Management Using Git & GitHub

## Project Overview
Aperture Technology previously used a source code management tool that resulted in
redundant code storage and frequent conflicts when multiple developers worked on the
same codebase simultaneously.

To resolve these issues, the company decided to migrate its entire codebase to **Git**
for version control and **GitHub** for centralized collaboration.

As assigned by the manager, Mike is responsible for performing this migration and
demonstrating proper Git workflows.

---

## Problem Statement
Three developers are working in Aperture Technology Co.  
The company wants a better Source Code Management System because:
- The earlier tool saved redundant code
- Multiple developers working on the same block of code caused conflicts

The objective is to migrate the existing codebase to Git and GitHub and demonstrate
branching and merging.

---

## Objectives
- Create a local Git repository and move the existing codebase into it
- Create a new feature branch
- Merge the feature branch into the master branch
- Create a remote GitHub repository
- Push the local repository to the remote repository

---

## Prerequisites
- Git installed on the system
- GitHub account
- Basic understanding of Git commands
- Existing application source code


## Step-by-Step Git Implementation
-git init
-git status
-git add .
-git commit -m "message"
-git checkout -b branch-name
-git checkout main
-git merge branch-name
-git remote add origin <repository-url>
-git push -u origin main