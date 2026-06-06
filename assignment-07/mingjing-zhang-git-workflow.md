# Assignment 07: Git Workflow

## Student Name
Mingjing Zhang

## Repository
cse632-0526

## Branch Name
feature/mingjing-zhang-assignment-07

## Commands Practiced
- git clone, git remote -v, git config user.name/user.email
- git checkout -b, git status, git add, git diff --staged
- git commit, git push, git fetch, git merge
- git log, git rev-parse HEAD

## Directories Created
- assignment-07/
- assignment-08/
- final_project/

## Git Remote Output
origin  https://github.com/mingjing-zhang/cse632-0526.git (fetch & push)

## Git Status Output
On branch feature/mingjing-zhang-assignment-07; new file assignment-07/mingjing-zhang-git-workflow.md staged for commit.

## Pull Request URL
TODO-PR-URL

## Latest Commit Hash
TODO-COMMIT-HASH

## Merge Conflict Summary
Cut branch B from main before merging branch A, so both branches edited README.md line 1. Merging origin/main into branch B produced a conflict on that line, which I resolved to the agreed title and committed.

## Reflection
Staging with git add lets me pick exactly what enters the next commit, which is separate from merely saving the file to disk; git diff --staged shows that staged snapshot before I lock it in. A commit is an immutable checkpoint identified by the hash returned by git rev-parse HEAD. Branches are cheap, movable pointers, so feature/mingjing-zhang-assignment-07 isolates my work from main until it is ready to review. A pull request is the controlled boundary where that branch is reviewed and merged into main on GitHub. Pushing publishes my local commits to origin so the PR and other people can see them. Fetch plus merge brings the remote main back into my branch, and when two branches change the same line Git stops and asks me to resolve the conflict by hand. Doing the README A/B exercise made the difference between a fast-forward and a real three-way merge concrete.
