# **Task-5 Interactive Rebase Commands**

---

### `git rebase -i HEAD~n`

* **Function:** Starts interactive rebase for the last `n` commits.
* **Effect:** Opens an editor to modify commit history (squash, reorder, edit messages).

---

### `pick`

* **Function:** Keeps the commit as it is.
* **Effect:** Commit remains unchanged in the new history.

---

### `reword`

* **Function:** Edits the commit message.
* **Effect:** Allows rewriting commit message without changing content.

---

### `squash`

* **Function:** Combines the current commit with the previous commit.
* **Effect:** Multiple commits are merged into one, preserving all changes.

---

### `fixup`

* **Function:** Combines commit with previous one but discards its message.
* **Effect:** Cleaner history without extra commit messages.

---