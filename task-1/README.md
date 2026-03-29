# TASK-1 COMMANDS AND ITS UTILITY
## 1. Initialize Repository

```bash
git init
```

* A hidden `.git` folder was created


## 2. Add File to Staging

```bash
git add .\file1.txt
```

**Function:** Moves file → **staging area**

* Git now *tracks* `file1.txt`
* Ready for commit

---

## 3. First Commit

```bash
git commit -m "feat:file1.txt added"
```

**Function:** Saves snapshot


* First commit created
* File permanently stored in history

---

## 4. Check Branch

```bash
git branch
```

**Function:** Lists branches


---

## 5. Create New Branch

```bash
git branch inno-feature
```

**Function:** Creates a new branch

* New branch created from current state (`master`)

---

## 6. Verify Branches

```bash
git branch
```

* `master` → current branch
* `inno-feature` → new branch exists

---

## 7. Switch Branch

```bash
git checkout inno-feature
```

**Function:** Switch to another branch

* HEAD moved to `inno-feature`


---

## 8. Check Status

```bash
git status
```

**Function:** Shows file states


* File is **modified**
* Not staged


---

## 9. Merge Feature Branch

```bash
git merge inno-feature
```

**Function:** Combine branches


* No conflict → smooth merge
* Master now includes feature changes


---

## 10. View Commit History

```bash
git log
```
**Function:** Shows commit history
