#Linux Package Management — APT Installation Activity

This report was completed as part of the **Google Cybersecurity Certificate**. It documents how to install, remove, and verify applications using the Advanced Package Tool (APT) in a Debian-based Linux Bash environment. The lab demonstrates how security analysts use CLI tools to manage software while maintaining a secure operating system.

---

## 🧑‍💻 Activity Scenario

As a security analyst, you're responsible for ensuring that key network security applications are installed and properly managed. In this activity, you:

- Verified that APT is available
- Installed and removed **Suricata**
- Installed **tcpdump**
- Reinstalled **Suricata**
- Verified application presence using `apt list --installed`

---

## 🛠️ My Contributions

### ✅ Step 1: Verify APT is Installed
Used the `apt` command to confirm presence of the Advanced Package Tool.  
APT returned usage information and confirmed version: `apt 2.2.4 (amd64)`

---

### ✅ Step 2: Install Suricata
Ran:
```bash
sudo apt install suricata

# 📦 Linux Application Management — APT Installation Lab

This lab report was completed as part of the **Google Cybersecurity Certificate**. It documents how to install, uninstall, and verify applications using the **Advanced Package Tool (APT)** in a Debian-based Linux Bash shell. The activity focuses on hands-on CLI usage to reinforce Linux package management techniques critical for a cybersecurity analyst.

---

## 🧑‍💻 Activity Overview

As a security analyst, you were tasked with managing two network traffic inspection tools — **Suricata** and **tcpdump** — in a virtual machine running a Debian-based Linux distribution. The lab required verifying APT availability, managing installations through `sudo`, and confirming application status through CLI queries.

---

## 🛠️ My Contributions

### ✅ Step 1: Verify APT is Installed
Ran:
```bash
apt
