## Task-3 Git Undo Commands


### `git restore <file>`
* **Function:** Discards uncommitted changes in  working directory.
* **Effect:** It overwrites  current file with the last committed version.Have to use this when something wrong but haven't run `git add` or `git commit` yet.

---

### `git revert <commit_id>`
* **Function:** Creates a **new** commit that records the exact inverse of a previous commit.
* **Effect:** It does not delete history. Instead, it adds a new "correction" commit to the chain. This is the safest way to undo changes that have already been pushed to a shared repo.


---

### `git reset --soft HEAD~1`
* **Function:** Moves the branch pointer back one commit but keeps  work in the **Staging Area**.
* **Effect:** The commit is "undone" in the log, but code changes are still there and marked as "Changes to be committed." This is perfect if want to fix a typo in  last commit message or add one more file to it.

---

### `git reset HEAD~1` (Mixed Reset)
* **Function:** Moves the branch pointer back one commit and removes the changes from the Staging Area.
* **Effect:** Work stays on system, but it shows up as **Unstaged**.Have to `git add` the files again if want to commit them. This is the default mode for `reset`.

---

### `git reset --hard HEAD~1`
* **Function:** Moves the branch pointer back and **permanently deletes** all changes in the working directory.
* **Effect:** This is the "Nuclear Option." It wipes the commit and the actual code from  files. There is no "Undo" for a hard reset, so use it only when want to completely scrap recent work.

---