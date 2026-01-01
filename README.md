# ConsTrack for Up-Tech Builders
### Repository Link:
https://github.com/Taklri/ConsTrackWeb.git

---

# Commands for Git
### Clone Repository (First Time Only)
```
git clone https://github.com/Taklri/ConsTrackWeb.git
```
### Move into the project folder
```
cd ConsTrackWeb
```
### Check Git Status
```
git status
```
### Add or Save the file
##### Add all changed files

```
git add .
```
### Add a specific file only
```
git add filename.ext
```
### Commit Changes
#### Save Changes with a message describing what you did
```
git commit -m "Sample Message"
```
### Pull latest Changes (MOST IMPORTANT)
#### Since gagamit us ng branch para makapag code tayo kanya kanya, bago isave yung gawa natin dapat ipull/kunin muna ung recent version ng "main" para updated ung code lagi

```
git pull origin main
```
### Push Changes
#### Upload commits to github repo
```
git push origin main
```
# Branch commands
### Create new Branch
#### bawal may space, use " - " na lang instead mag space
```
git branch feature-login
```
### Switch Branch
```
git checkout feature-login
```
### Create + Switch at the same time
```
git checkout -b feature-login
```
### Push a Branch to Github
```
git push origin feature-login
```
### Switch back to Main
```
git checkout main
```
### Merge Branch into Main
#### Madalas magagamit to. Make sure na na sa main muna and nakapag git add . na sa branch
```
git checkout main
git pull origin main
```
#### merge
```
git merge feature-login
```
# Helpful Git Commands
### View Commit history
```
git log
```
### See differences
```
git diff
```
### Temporarily save changes
```
git stash
```
### Apply stashed changes
```
git stash pop
```
# IMPORTANT RULES
- Always pull before pushing
- Use branches for features/modules
- Write clear commit messages para mas madali ma identify
