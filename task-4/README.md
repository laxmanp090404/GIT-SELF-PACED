# **Task-4 Merge Conflict Commands**

---

### `git branch <branch-name>`

* **Function:** Creates a new branch from the current commit.
* **Effect:** Used to create parallel versions of the project for independent changes.

---

### `git checkout <branch-name>`

* **Function:** Switches to another branch.
* **Effect:** Moves `HEAD` to the selected branch so changes apply there.

---

### `git merge <branch-name>`

* **Function:** Merges the specified branch into the current branch.
* **Effect:** Combines histories. If same lines are modified → **merge conflict occurs**.

---

### `git status`

* **Function:** Shows the current state of the repository.
* **Effect:** Displays files with conflicts (e.g., *both modified*) and guides next steps.

---

### `git diff`

* **Function:** Shows differences between conflicting changes.
* **Effect:** Helps identify what each branch changed in the same file.

---

### `git merge --abort`

* **Function:** Cancels the ongoing merge process.
* **Effect:** Restores repository to state before merge started.

---