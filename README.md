# 🧭 Command Line Essentials – From Beginner to Power User

> Original article on Medium: [Master the Command Line – Practical CLI Guide for Students & Developers](https://medium.com/@samnaufer0401/master-the-command-line-practical-cli-guide-for-students-developers-60634fb8e788)

*A complete, practical, and beginner-friendly guide for students, developers, and IT learners.*

## ✨ Why Learn the Command Line?

The **Command Line Interface (CLI)** allows you to interact directly with your operating system using text commands instead of graphical buttons.

### 🚀 Benefits:

- Faster than GUI once mastered
- Essential for **software development**, **networking**, **cloud**, and **DevOps**
- Required for servers (Linux servers have no GUI)
- Improves problem-solving & system understanding

> If you can use the terminal confidently, **you are already ahead of most beginners**.

Read more: [Medium article](https://medium.com/@samnaufer0401/master-the-command-line-practical-cli-guide-for-students-developers-60634fb8e788)

---

## 📍 1. Navigation – Moving Around the File System

| Task | 🟧 macOS / Linux | 🟦 Windows (CMD / PowerShell) |
|------|-----------------|------------------------------|
| Show current directory | `pwd` | `cd` |
| List files & folders | `ls` | `dir` |
| Move into a folder | `cd folder_name` | `cd folder_name` |
| Go back one level | `cd ..` | `cd ..` |
| Go to Home directory | `cd ~` | `cd %USERPROFILE%` |

### 📌 Example (Same on Both Platforms)

| Action | Command |
|--------|--------|
| Go to Documents | `cd Documents` |
| Go to Projects | `cd Projects` |

---

## 📁 2. File & Folder Management

| Task | 🟧 macOS / Linux | 🟦 Windows |
|------|-----------------|-----------|
| Create folder | `mkdir project` | `mkdir project` |
| Create empty file | `touch index.html` | `ni file.txt` |
| Copy file | `cp file1.txt file2.txt` | `copy a.txt b.txt` |
| Move / Rename | `mv old.txt new.txt` | `move old.txt new.txt` |
| Delete file | `rm file.txt` | `del file.txt` |
| Delete folder | `rm -rf folder` | `rmdir /s folder` |

> ⚠️ **Warning:** `rm -rf` and `rmdir /s` permanently delete files and folders.

Learn more in the original article: [Medium link](https://medium.com/@samnaufer0401/master-the-command-line-practical-cli-guide-for-students-developers-60634fb8e788)

---

## 🌐 3. System & Network Commands

| Task | 🟧 macOS / Linux | 🟦 Windows |
|------|-----------------|-----------|
| Clear terminal | `clear` | `cls` |
| Show IP address | `ifconfig` | `ipconfig` |
| Test internet | `ping google.com` | `ping google.com` |
| Show running processes | `top` | `tasklist` |

---

## 🔎 4. Searching Files & Content

| Task | 🟧 macOS / Linux | 🟦 Windows |
|------|-----------------|-----------|
| Find file by name | `find . -name file.txt` | `dir /s file.txt` |
| Search inside file | `grep "text" file.txt` | `findstr "text" file.txt` |
| Print file content | `cat file.txt` | `type file.txt` |
| Scroll through file | `less file.txt` | `more file.txt` |

---

## 🔐 5. Permissions & Security (macOS/Linux)

| Task | Command |
|------|---------|
| View permissions | `ls -la` |
| Change file permission | `chmod 755 script.sh` |
| Change file owner | `chown user:group file` |
| Run as administrator | `sudo command` |

Windows equivalent (PowerShell):

```powershell
Start-Process -Verb runAs   # Run as admin
