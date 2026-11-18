# Questions and Answers

### 1. What is the difference between git fetch and git pull?
- `git fetch` downloads updates but does not merge them.
- `git pull` downloads updates and merges them into your branch.

### 2. When should you use revert instead of reset?
Use `git revert` to undo a commit safely without deleting it from the history.

### 3. Why is rebase dangerous on shared branches?
Rebase changes commit history. It can cause problems for teammates who are using the same commits.

### 4. What does git reset --hard do, and how can reflog help?
- `git reset --hard` removes uncommitted changes and moves your branch to another commit.
- `git reflog` helps you find and recover lost commits.

### 5. How do you find which commit introduced a bug?
Use `git bisect` to test commits and find the one that introduced the bug.

