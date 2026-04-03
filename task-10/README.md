# **Task-10 Forced Push & Recovery Commands**

### `git checkout -b <branch>`

* **Function:** Creates and switches to a new branch.
* **Effect:** Used to isolate work for rewriting history safely.

---


### `git push -u origin <branch-name>`

* **Function:** Pushes branch to remote and sets upstream.
* **Effect:** Links local branch with remote branch.

---

### `git rebase -i HEAD~n`

* **Function:** Starts interactive rebase for last `n` commits.
* **Effect:** Allows squashing, editing, or reordering commits.

---

### `squash`

* **Function:** Combines commits during rebase.
* **Effect:** Creates a cleaner commit history.

---

### `git push --force`

* **Function:** Forces update of remote branch after history rewrite.
* **Effect:** Overwrites remote history with local history.

---

### `git reset --hard HEAD~1`

* **Function:** Moves branch pointer backward and deletes latest commit.
* **Effect:** Simulates accidental loss of commits.

---

### `git reflog`

* **Function:** Displays history of HEAD movements.
* **Effect:** Helps locate lost commits.

---

### `git reset --hard <commit-hash>`

* **Function:** Restores repository to a specific commit.
* **Effect:** Recovers lost commits from reflog.

---