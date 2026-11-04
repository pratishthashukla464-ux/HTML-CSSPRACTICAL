
Aim:
To send commits to a second repository on the computer and make a copy of it using Git Clone.

Requirements:
Git
Command Prompt or Git Bash
Existing html-lab repository

Task 1: Create a Bare Repository

Commands:
cd html-lab
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v

Task 2: Push Commits

Command:
git push origin main

Task 3: Clone Repository

Commands:
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline

Result:
Successfully created a remote repository, pushed commits and cloned the repository.