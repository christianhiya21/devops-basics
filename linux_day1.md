# 🐧 Linux - Day 1: Navigation & Basic Commands

## 📘 Overview
Linux is an open-source operating system widely used in DevOps, cloud, and server environments.  
Today’s focus: learning basic file and directory navigation commands using the terminal.

---

## 📂 1. Directory Navigation

| Command | Description | Example |
|----------|--------------|----------|
| `pwd` | Prints the current working directory | `pwd` |
| `ls` | Lists files and folders in the current directory | `ls -l` |
| `cd foldername` | Changes directory to *foldername* | `cd Documents` |
| `cd ..` | Moves one level up | `cd ..` |
| `cd /` | Moves to the root directory | `cd /` |

---

## 📁 2. File and Folder Management

| Command | Description | Example |
|----------|--------------|----------|
| `mkdir foldername` | Creates a new folder | `mkdir devops` |
| `rmdir foldername` | Removes an empty folder | `rmdir test` |
| `touch filename` | Creates a new empty file | `touch notes.txt` |
| `cp source destination` | Copies a file | `cp notes.txt copy.txt` |
| `mv source destination` | Moves or renames a file | `mv copy.txt devops/` |
| `rm filename` | Deletes a file | `rm notes.txt` |

---

## 📄 3. Viewing Files

| Command | Description | Example |
|----------|--------------|----------|
| `cat filename` | Displays file content | `cat notes.txt` |
| `less filename` | Opens file in a scrollable view | `less notes.txt` |
| `head -n 5 filename` | Shows first 5 lines | `head -n 5 notes.txt` |
| `tail -n 5 filename` | Shows last 5 lines | `tail -n 5 notes.txt` |

---

## 🧠 4. Notes / Learnings

- Everything in Linux is a **file** (even devices and processes).
- Case-sensitive file names (`Notes.txt` ≠ `notes.txt`).
- Use `Tab` for auto-completion.
- Use `Ctrl + L` to clear the terminal screen.
- Use `history` to see previous commands.

---

## ✅ Task Completed
- Practiced 10+ Linux commands  
- Created this markdown file  
- Committed and pushed to GitHub repository: `devops-basics`

---

🕒 *Date:* 1 November 2025  
👩‍💻 *By:* Hiya  
