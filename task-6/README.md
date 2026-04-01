# **Task-6 Git Stash Commands**


### `git stash`

* **Function:** Temporarily saves uncommitted changes (both staged and unstaged).
* **Effect:** Clears the working directory and stores changes in a stash stack for later use.

---

### `git stash pop`

* **Function:** Applies the most recent stash and removes it from the stash list.
* **Effect:** Restores previously saved changes back into the working directory.

---

### `git stash apply`

* **Function:** Applies a specific stash without removing it from the stash list.
* **Effect:** Allows reuse of the same stash multiple times if needed.

---

### `git stash list`

* **Function:** Displays all saved stashes.
* **Effect:** Shows stash entries like `stash@{0}`, `stash@{1}` for reference.

---

### `git stash drop <stash@{n}>`

* **Function:** Deletes a specific stash from the stash list.
* **Effect:** Removes unwanted or already used stashes.

---

### `git stash -u`

* **Function:** Stashes both tracked and untracked files.
* **Effect:** Ensures even newly created files are saved in the stash.

---

### `git stash clear`

* **Function:** Deletes all stashes.
* **Effect:** Completely clears the stash stack.

---