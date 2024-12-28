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



# DevOps Learning Resources 🚀

Welcome to my curated list of DevOps resources! This repository serves as a hub for all the tools, courses, blogs, and guides I've explored and found valuable in my DevOps journey.

---

## Table of Contents 📚
1. [Introduction to DevOps](#introduction-to-devops)
2. [Tools and Technologies](#tools-and-technologies)
3. [Courses and Certifications](#courses-and-certifications)
4. [Books](#books)
5. [Blogs and Websites](#blogs-and-websites)
6. [YouTube Channels](#youtube-channels)
7. [Cheat Sheets and Guides](#cheat-sheets-and-guides)
8. [Communities and Forums](#communities-and-forums)
9. [Projects and Hands-On Practice](#projects-and-hands-on-practice)

---

## Introduction to DevOps
> **What is DevOps?**  
> DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to shorten the development lifecycle while delivering features, fixes, and updates frequently and reliably.

---

## Tools and Technologies 🛠️
Here’s a list of essential DevOps tools and platforms:
- **Version Control**: [Git](https://git-scm.com), [GitHub](https://github.com)
- **CI/CD**: [Jenkins](https://www.jenkins.io), [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)
- **Containerization**: [Docker](https://www.docker.com), [Podman](https://podman.io)
- **Orchestration**: [Kubernetes](https://kubernetes.io), [OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift)
- **Infrastructure as Code**: [Terraform](https://www.terraform.io), [Ansible](https://www.ansible.com)
- **Monitoring and Logging**: [Prometheus](https://prometheus.io), [Grafana](https://grafana.com), [ELK Stack](https://www.elastic.co/what-is/elk-stack)
- **Cloud Platforms**: [AWS](https://aws.amazon.com), [Azure](https://azure.microsoft.com), [Google Cloud](https://cloud.google.com)

---

## Courses and Certifications 🎓
- **Beginner Courses**:
  - [DevOps for Beginners (Udemy)](https://www.udemy.com)
  - [Introduction to DevOps (Coursera)](https://www.coursera.org)
- **Advanced Courses**:
  - [Certified Kubernetes Administrator (CKA) by Linux Foundation](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/)
  - [AWS Certified DevOps Engineer](https://aws.amazon.com/certification/certified-devops-engineer-professional/)
- **Certifications**:
  - [AWS Certified DevOps Engineer](https://aws.amazon.com/certification/)
  - [Google Professional DevOps Engineer](https://cloud.google.com/certification)

---

## Books 📘
- *The Phoenix Project* by Gene Kim
- *The DevOps Handbook* by Gene Kim, Patrick Debois, John Willis, and Jez Humble
- *Site Reliability Engineering* by Google SRE Team
- *Kubernetes Up & Running* by Brendan Burns, Joe Beda, and Kelsey Hightower

---

## Blogs and Websites 📝
- [AWS Blog](https://aws.amazon.com/blogs/)
- [DevOps.com](https://devops.com/)
- [HashiCorp Blog](https://www.hashicorp.com/blog/)
- [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io)

---

## YouTube Channels 🎥
- [TechWorld with Nana](https://www.youtube.com/c/TechWorldwithNana)
- [FreeCodeCamp](https://www.youtube.com/c/Freecodecamp)
- [Kunal Kushwaha](https://www.youtube.com/c/KunalKushwaha)
- [CloudAcademy](https://www.youtube.com/user/CloudAcademyInc)

---

## Cheat Sheets and Guides 📑
- [Docker Cheat Sheet](https://dockerlabs.collabnix.com/docker/cheatsheet/)
- [Kubernetes Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
- [Linux Command Cheat Sheet](https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/)

---

## Communities and Forums 🌐
- [DevOps Subreddit](https://www.reddit.com/r/devops/)
- [Stack Overflow](https://stackoverflow.com)
- [Kubernetes Slack](https://slack.k8s.io)
- [DevOps Discord](https://discord.com/invite/devops)

---

## Projects and Hands-On Practice 💻
- Build a CI/CD pipeline using Jenkins and Docker.
- Deploy a Kubernetes cluster and manage pods.
- Create an infrastructure with Terraform on AWS.
- Monitor a web application using Prometheus and Grafana.

---

## Contributions
If you have a great resource that should be added to this list, feel free to contribute by contacting me!

---

**Let’s keep learning and building!** 💡  
*Happy DevOps-ing!* 🌟

