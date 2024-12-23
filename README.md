# Windows File System and Batch Commands

This repository contains a collection of essential Windows file system and batch commands with explanations and usage examples. It serves as a guide for beginners to understand and work with Windows command-line tools effectively.

## **Commands Covered**

### **File System Navigation**
- `cd` - Change directory
- `dir` - List files and directories
- `pwd` - Print working directory (via `echo %cd%`)
- `cls` - Clear the screen

### **File and Directory Operations**
- `mkdir` - Create a directory
- `rmdir` - Remove a directory
- `copy` - Copy files
- `move` - Move files
- `del` - Delete files
- `ren` - Rename files or directories

### **File Viewing**
- `type` - Display the content of a file

### **Process Management**
- `tasklist` - List running processes
- `taskkill` - Terminate a process

### **Batch Scripting**
- `@echo off` - Turn off command echoing
- `set` - Manage environment variables
- `if` - Conditional logic
- `for` - Looping

---

## **How to Use**
1. Open Command Prompt (`cmd`) on your Windows system.
2. Navigate to the desired directory using `cd`.
3. Try out the commands with provided examples.

---

## **Batch Script Example**
Here's an example batch script to demonstrate these commands:

```bat
@echo off
echo Welcome to Windows Command Line Guide!
mkdir DemoFolder
cd DemoFolder
echo This is a test file > test.txt
type test.txt
cd ..
rmdir DemoFolder /s /q
echo All tasks completed!
pause


# macOS and Linux File System Commands

This repository contains a collection of essential macOS and Linux file system commands with explanations and usage examples. It is designed to help beginners learn and navigate the terminal efficiently.

---

## **Commands Covered**

### **File System Navigation**
- `cd` - Change directory
- `pwd` - Print working directory
- `ls` - List directory contents

### **File and Directory Operations**
- `mkdir` - Create a directory
- `rmdir` - Remove an empty directory
- `rm` - Remove files or directories
- `cp` - Copy files or directories
- `mv` - Move or rename files and directories

### **File Viewing**
- `cat` - View the content of a file
- `less` - View a file one screen at a time
- `head` - Display the first few lines of a file
- `tail` - Display the last few lines of a file

### **File Permissions**
- `chmod` - Change file permissions
- `chown` - Change file ownership

### **Disk and System Information**
- `df` - Display disk space usage
- `du` - Show directory or file size
- `top` - Display running processes
- `ps` - Show currently running processes

### **Networking**
- `ping` - Test connectivity to a host
- `curl` - Make HTTP requests
- `wget` - Download files from the web

---

## **How to Use**
1. Open the Terminal on macOS or Linux.
2. Navigate to the desired directory using `cd`.
3. Try out the commands with provided examples.

---

## **Example Script**
Here's a sample script that demonstrates some of these commands:

```bash
#!/bin/bash
echo "Welcome to macOS/Linux Command Line Guide!"

# Create a new directory
mkdir DemoFolder
cd DemoFolder

# Create and view a file
echo "This is a test file" > test.txt
cat test.txt

# Display disk usage
df -h

# Clean up
cd ..
rm -r DemoFolder
echo "All tasks completed!"
