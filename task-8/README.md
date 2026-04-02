# **Task-8 Git Hooks (Pre-Commit) Commands**


### `cd .git/hooks`

* **Function:** Navigates to the Git hooks directory.
* **Effect:** Allows creation and management of hook scripts.

---

### `notepad pre-commit`

* **Function:** Creates or opens the `pre-commit` hook file.
* **Effect:** Used to write custom logic that runs before every commit.

---

### `chmod +x pre-commit`

* **Function:** Makes the hook script executable.
* **Effect:** Ensures Git can run the script during commit.

---

### `git diff --cached`

* **Function:** Shows staged changes.
* **Effect:** Used inside the hook to inspect code before committing.

---

# Git Hooks

* **Function:** Automate tasks during Git lifecycle events.
* **Effect:** Enforces rules like linting, testing, and validation before commits.

---

# Pre-Commit Hook Behavior

* Runs automatically before every commit
* Checks staged changes (`git diff --cached`)
* Blocks commit if unwanted patterns (e.g., `"error"`) are found
* Allows commit if all checks pass

---