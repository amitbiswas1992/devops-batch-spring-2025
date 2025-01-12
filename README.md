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



### Networking for DevOps Engineers

Welcome to the **Networking for DevOps Engineers** documentation! This guide provides an overview of essential networking concepts, tools, and practical examples tailored for DevOps professionals.

## **Table of Contents**
1. [Introduction](#introduction)
2. [Key Topics Covered](#key-topics-covered)
3. [How to Use This Document](#how-to-use-this-document)
4. [Networking Concepts](#networking-concepts)
   - [OSI Model](#1-osi-model)
   - [Networking Protocols](#2-networking-protocols)
   - [IP Addressing](#3-what-is-an-ip-address)
   - [Ports](#4-ports)
   - [Subnetting](#5-subnetting)
   - [Routing](#6-routing)
   - [DNS](#7-dns-domain-name-system)
   - [VPN](#8-vpn-virtual-private-network)
5. [Networking Tools](#9-networking-tools)
6. [Advanced Networking Topics](#advanced-networking-topics)
7. [Practical Scenarios](#practical-scenarios)
8. [Resources](#resources)

---

## **Introduction**
This guide is designed to help DevOps engineers understand and implement networking principles effectively. Whether you're troubleshooting connectivity issues, configuring cloud infrastructure, or ensuring secure communication, these concepts are foundational.

---

## **Key Topics Covered**
- OSI Model
- TCP, UDP, and IP Protocols
- IP Addressing (IPv4 and IPv6)
- Ports and Port Forwarding
- Subnetting and CIDR Notation
- Routing and NAT
- DNS Configuration
- VPN for Secure Communication
- Essential Networking Tools
- Firewalls and Load Balancers

---

## **How to Use This Document**
1. **Learning**: Use this guide as a reference for understanding networking concepts step-by-step.
2. **Practical Applications**: Implement the provided examples in your daily DevOps workflows.
3. **Troubleshooting**: Refer to specific sections to resolve network-related issues in cloud or local environments.

---

## **Networking Concepts**
### **1. OSI Model**
- Learn about the 7 layers of the OSI model and their roles in networking.
- [Detailed Explanation](https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/)

### **2. Networking Protocols**
- Understand TCP, UDP, and IP protocols with real-world examples.
- Learn the differences between connection-oriented (TCP) and connectionless (UDP) communication.

### **3. What is an IP Address?**
- Learn about IPv4 and IPv6 addressing formats (e.g., `123.123.1.231`).
- Understand private vs public IP addresses and their uses.

### **4. Ports**
- Explore the role of ports in networking and their importance for DevOps tasks.
- Examples: Ports 80 (HTTP), 443 (HTTPS), and 22 (SSH).

### **5. Subnetting**
- Dive into subnetting and CIDR notation to manage IP spaces efficiently.

### **6. Routing**
- Understand how routing works and how to configure routing tables for cloud and local networks.

### **7. DNS (Domain Name System)**
- Learn how DNS translates domain names into IP addresses and vice versa.

### **8. VPN (Virtual Private Network)**
- Explore how VPNs create secure communication tunnels over the internet.

---

## **9. Networking Tools**
Master essential tools for DevOps networking:
- `ping`: Test connectivity.
- `traceroute`: Track the path of packets.
- `netstat`: View active network connections.
- `nmap`: Discover hosts and services.
- `tcpdump`: Capture and analyze network traffic.
- `Wireshark`: Visualize and troubleshoot network interactions.

---

## **Advanced Networking Topics**
1. **Network Address Translation (NAT)**: Map private IPs to public IPs for internet access.
2. **Load Balancing**: Distribute traffic across multiple servers for redundancy.
3. **Firewalls**: Secure networks by controlling incoming and outgoing traffic.

---

## **Practical Scenarios**
1. Configuring CI/CD pipelines for secure artifact deployments across regions.
2. Troubleshooting Docker container communication issues.
3. Setting up secure VPN access to remote cloud environments.

---

## **Resources**
- [OSI Model Explanation](https://www.geeksforgeeks.org/open-systems-interconnection-model-osi/)
- [TCP/UDP Basics](https://www.pluralsight.com/blog/it-ops/networking-basics-tcp-udp-tcpip-osi-models)
- [Subnetting Video Tutorial](https://youtu.be/I_LXaIg6mkM?si=H71TnHbE8oOVfMzp)
- [Cloudflare - What is a Port?](https://www.cloudflare.com/en-in/learning/network-layer/what-is-a-computer-port/)
- [Top Networking Tools for DevOps](https://www.geeksforgeeks.org/top-15-networking-tools-that-you-must-know-as-a-devops-engineer/)

---


### **Examples**

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

