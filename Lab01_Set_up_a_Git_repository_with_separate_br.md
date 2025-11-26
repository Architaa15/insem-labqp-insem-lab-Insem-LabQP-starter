# Lab 01: Set up a Git repository with separate branches for frontend and backend, then merge them into the main branch.

## Objective
Describe the objective of this lab here.
Set up a Git repository, create separate branches for frontend and backend, work on each, and merge them into the main branch.
## Tools / Technologies
List the tools and technologies required (e.g., Git, GitHub, Docker, Jenkins).
Git
GitHub account
Terminal / Git Bash / VS Code
## Prerequisites
Describe any prerequisites (installed software, configured accounts, etc.).
Git installed
GitHub account ready
Basic understanding of Git commands

## Steps / Commands
1. Initialize Repository
git init
git remote add origin <repo-url>


Creates a new local Git repo and links it to GitHub.

2. Create Frontend Branch
git checkout -b frontend


Add any sample frontend file, then:

git add .
git commit -m "Add frontend code"
git push origin frontend

3. Create Backend Branch
git checkout main
git checkout -b backend


Add backend file, then:

git add .
git commit -m "Add backend code"
git push origin backend

4. Merge Both Branches Into Main

Switch to main:

git checkout main


Merge frontend:

git merge frontend


Merge backend:

git merge backend


Push main:

git push origin main

## Expected Output / Result
Describe expected outputs, screenshots to capture, or verification steps.
A GitHub repo with 3 branches:
main, frontend, backend

Both frontend and backend code merged into main

No merge conflicts (or resolved if they appear)

Screenshot of branches page in GitHub

## Deliverables (what to push)
- `Labs/Lab01_<ShortTitle>.md` (this file, completed)
- Any additional scripts, Dockerfiles, manifests, or screenshots placed in a folder named `Lab01_files/`

## Notes / Tips
- Add any helpful hints or troubleshooting tips here.
- Keep commands and outputs clear for grading.

