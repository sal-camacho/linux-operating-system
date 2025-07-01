# Linux File Permissions

This project demonstrates hands-on exploration of Linux file permission structures using real CLI tools. It focuses on securing files and directories through permission management—an essential skill in system administration and cybersecurity.

## 🧰 Environment
- **Operating System**: Debian-based Linux
- **Tools Used**: `chmod`, `chown`, `ls`, `chmod -R`
- **Objective**: Understand and apply symbolic and numeric permission modes to manage file access securely

## 🔍 What This Project Covers
- Interpreting symbolic (`rwx`) and numeric (`chmod 755`) file permission structures
- Changing ownership and access rights using `chmod` and `chown`
- Practicing recursive permission changes with `chmod -R` on directories
- Real-world examples to simulate securing sensitive files

## 📁 Repository Contents
```basic-filepermissions/
├── basic-filepermissions.txt   # Hands-on examples and notes about Linux file permissions
└── README.md                   # Project overview and learning objectives
```

## 📄 Example Command
```bash
chmod 750 confidential-report.txt
```
