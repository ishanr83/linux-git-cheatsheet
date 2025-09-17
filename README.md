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
