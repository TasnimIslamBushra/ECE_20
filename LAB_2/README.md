

# Basic Git Commands

## 1. Git Configuration

### `git config`
Set up user information like name and email.

**Example:**
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

---

## 2. Initialize a Repository

### `git init`
Initialize a new Git repository.

**Example:**
```bash
git init
```

---

## 3. Clone a Repository

### `git clone`
Create a local copy of a remote repository.

**Example:**
```bash
git clone https://github.com/username/repo-name.git
```

---

## 4. Check Repository Status

### `git status`
Check the current status of files in the working directory and staging area.

**Example:**
```bash
git status
```

---

## 5. Stage Changes

### `git add`
Add files to the staging area.

**Examples:**
- Add a single file:
```bash
git add filename.txt
```

- Add all files:
```bash
git add .
```

---

## 6. Commit Changes

### `git commit`
Commit staged changes with a message.

**Example:**
```bash
git commit -m "Add new feature"
```

---

## 7. Push Changes

### `git push`
Push local commits to the remote repository.

**Example:**
```bash
git push origin main
```

---

## 8. Pull Changes

### `git pull`
Fetch and merge changes from the remote repository to your local branch.

**Example:**
```bash
git pull origin main
```




---

## Conclusion
These basic Git commands cover the essential workflow for most projects, from initializing a repository to branching and merging.
```