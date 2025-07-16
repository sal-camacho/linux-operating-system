# Linux File Permissions

This project demonstrates hands-on exploration of Linux file permission structures using real CLI tools. It focuses on securing files and directories through permission management—an essential skill in system administration and cybersecurity.

## 🧰 Environment
- **Operating System**: Debian-based Linux
- **Tools Used**: `chmod`, `ls`, `ls -l`, `ls -la`
- **Objective**: Understand and apply symbolic and numeric permission modes to manage file access securely

## 🔍 What This Project Covers
- Reading and interpreting symbolic (rwx) file permission structures using ls -l and ls -la
- Modifying access rights for users, groups, and others using `chmod`  
- Exploring hidden files and permission flags with `ls -la`  
- Adjusting directory visibility and access through permission changes  
- Modifying file and directory permissions using symbolic mode to manage access securely
- Real-world examples to simulate securing sensitive files

## 📁 Repository Contents
```text
basic-filepermissions/
├── basic-filepermissions.txt   # Hands-on examples and notes about Linux file permissions
└── README.md                   # Project overview and learning objectives
```

## 📄 Example Commands
```bash
chmod u-w,g-w,g+r .project_x.txt    # Remove write access from user/group, add read for group
chmod g-x drafts                    # Prevent group from accessing the drafts directory
```
