# How to Create a Pull Request (PR)

## What is a PR?
- A **Pull Request** is how you ask to add your changes to the main project
- It lets maintainers review your work

## Before you create a PR
- You have:
  - Forked the repo
  - Cloned it
  - Made a branch
  - Committed your changes
  - Pushed your branch

Quick commands check:
- git status
- You should see: “nothing to commit, working tree clean”

## Create the PR (GitHub website)
- Go to your fork on GitHub
- You will often see:
  - **Compare & pull request**
- If you don’t see it:
  - Click **Pull requests** → **New pull request**

## Fill the PR details
- Title:
  - Keep it short
  - Example: “Fix typo in docs”
- Description:
  - What you changed
  - Why you changed it
  - If it fixes an issue, write: “Fixes #<issue-number>”

## Add screenshots (optional)
- If you changed text or docs, screenshots are optional
- Placeholder you can use:
  - <!-- Screenshot: add image here if needed -->

## After you open a PR
- A maintainer may comment
- You can update the same PR by pushing more commits:
  - Edit files

    git add .
    git commit -m "Address review comments"
    git push

## If your PR shows conflicts
- Don’t panic
- Read: [How to Fix Merge Conflicts](how-to-fix-merge-conflicts.md)

## Next
- Try a beginner task: [practice/simple-task.md](../practice/simple-task.md)
