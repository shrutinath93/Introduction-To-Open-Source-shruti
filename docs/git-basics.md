# Git Basics (Beginner)

## What is Git?
- Git is a tool to track changes in files
- It helps you:
  - Save your work (history)
  - Work in branches
  - Share changes with others

## 4 commands you will use the most

### 1) Check status
- See what changed:

    git status

### 2) See changes
- View file changes:

    git diff

### 3) Stage changes
- Pick what goes into the commit:

    git add .
- Or add one file:

    git add docs/git-basics.md

### 4) Commit changes
- Save a snapshot with a message:

    git commit -m "Explain git add and commit"

## Branches (simple)
- A branch is your own “work lane”
- Create a branch:

    git checkout -b my-branch-name
- Switch back to main:

    git checkout main

## Push (send changes to GitHub)
- First push for a new branch:

    git push -u origin my-branch-name

## Pull (get updates from GitHub)
- If upstream is set:

    git pull

## A tiny example flow
- git status
- Edit a file
- git add .
- git commit -m "Update instructions"
- git push

## Common mistakes
- “Nothing to commit”
  - You forgot git add
- “Rejected / failed to push”
  - Your branch is behind
  - Try git pull then push again

## Next
- Read: [How to Commit](how-to-commit.md)
- Then: [How to Push](how-to-push.md)
