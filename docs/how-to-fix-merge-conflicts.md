# How to Fix Merge Conflicts (Template)

## What is a merge conflict?
- Git can’t auto-merge two different edits in the same lines
- It asks you to choose what the final text should be

## Basic steps
- Pull latest changes:
  - `git checkout main`
  - `git pull`
- Go back to your branch:
  - `git checkout <your-branch>`
- Merge main into your branch:
  - `git merge main`

## If conflicts happen
- Open the conflicted file
- Look for markers:
  - `<<<<<<<`
  - `=======`
  - `>>>>>>>`
- Edit the file so it looks correct
- Remove the markers
- Then:
  - `git add <file>`
  - `git commit -m "Resolve merge conflict"`
  - `git push`

## Next
- Go back to your PR and refresh
