# Linux & Git Command Cheat Sheet

Created in Vim from the terminal and versioned with Git — one branch per command, merged back into `main` after each addition.

## How to Use This
Each entry shows: **What it does • Syntax • Example**

---

## Linux Commands (8)
1. pwd
2. ls
3. cd
4. mkdir
5. touch
6. cp
7. mv
8. rm

## Git Commands (7)
9. git init
10. git status
11. git add
12. git commit
13. git branch
14. git checkout (or git switch)
15. git merge

### pwd
- **What it does:** Prints the current working directory.
- **Syntax:** `pwd`
- **Example:**
  ```bash
  pwd
### ls
- **What it does:** Lists files and directories (use `-la` for long + hidden).
- **Syntax:** `ls [options] [path]`
- **Example:**
  ```bash
  ls -la
### cd
- **What it does:** Changes the current directory.
- **Syntax:** `cd <path>`
- **Example:**
  ```bash
  cd /var/log

### mkdir
- **What it does:** Creates directories.
- **Syntax:** `mkdir [-p] <dir>`
- **Example:**
  ```bash
  mkdir -p projects/demo
### touch
- **What it does:** Creates an empty file or updates its timestamp.
- **Syntax:** `touch <file>`
- **Example:**
  ```bash
  touch notes.txt

### cp
- **What it does:** Copies files or directories.
- **Syntax:** `cp [options] <source> <dest>`
- **Example:**
  ```bash
  cp file.txt backup/file.txt

### mv
- **What it does:** Moves or renames files.
- **Syntax:** `mv <source> <dest>`
- **Example:**
  ```bash
  mv draft.md README.md
### rm
- **What it does:** Removes files or directories (careful).
- **Syntax:** `rm [-rfi] <path>`
- **Example:**
  ```bash
  rm -rf build/
### git init
- **What it does:** Initializes a new Git repository in the current directory.
- **Syntax:** `git init`
- **Example:**
  ```bash
  git init
### git status
- **What it does:** Shows changed, staged, and untracked files.
- **Syntax:** `git status`
- **Example:**
  ```bash
  git status
### git add
- **What it does:** Stages changes to be committed.
- **Syntax:** `git add <file>` | `git add .`
- **Example:**
  ```bash
  git add README.md

### git commit
- **What it does:** Saves staged changes with a message.
- **Syntax:** `git commit -m "message"`
- **Example:**
  ```bash
  git commit -m "Add ls command section"

