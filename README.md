# File System and Command Line Commands Guide

This repository provides a comprehensive guide to essential file system and command-line commands for **Windows**, **macOS**, and **Linux**. It includes explanations and usage examples to help users effectively navigate, automate, and manage their systems using the terminal or command prompt.

---

## **Commands Covered**

### **File System Navigation**
- `cd` - Change directory.
  - `cd ..` - Move to the parent directory.
  - `cd ~` (macOS/Linux) - Move to the home directory.
  - `cd \` (Windows) - Move to the root directory.
- `pwd` - Print working directory.
  - `pwd` (macOS/Linux).
  - `echo %cd%` (Windows).
- `ls` (macOS/Linux) / `dir` (Windows) - List directory contents.

### **File and Directory Operations**
- `mkdir` - Create a new directory.
- `rmdir` (Windows/macOS/Linux) - Remove an empty directory.
  - `rmdir /s` (Windows) - Remove a directory and its contents.
- `rm` (macOS/Linux) - Remove files or directories.
- `cp` (macOS/Linux) / `copy` (Windows) - Copy files or directories.
- `mv` (macOS/Linux) / `move` (Windows) - Move or rename files and directories.
- `ren` (Windows) - Rename files or directories.

### **File Viewing**
- `cat` (macOS/Linux) / `type` (Windows) - Display the content of a file.
- `less` (macOS/Linux) - View a file one screen at a time.
- `head` (macOS/Linux) - Display the first few lines of a file.
- `tail` (macOS/Linux) - Display the last few lines of a file.

### **File Permissions**
- `chmod` (macOS/Linux) - Change file permissions.
- `chown` (macOS/Linux) - Change file ownership.

### **Process Management**
- `tasklist` (Windows) / `ps` (macOS/Linux) - List running processes.
- `taskkill` (Windows) - Terminate a process.
- `kill` (macOS/Linux) - Terminate a process.
- `top` (macOS/Linux) - Display system performance and running processes.

### **Networking**
- `ping` - Test connectivity to a host.
- `curl` - Make HTTP requests.
- `wget` - Download files from the web.

---

## **Examples**

### **Windows Batch Script Example**
A simple batch script demonstrating Windows commands:

```bat
@echo off
echo Welcome to Windows Command Line Guide!

# Create a directory
mkdir DemoFolder
cd DemoFolder

# Create and view a file
echo This is a test file > test.txt
type test.txt

# Return and clean up
cd ..
rmdir DemoFolder /s /q
echo All tasks completed!
pause
