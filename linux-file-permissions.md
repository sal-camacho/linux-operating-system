# Activity Overview
In this activity, you’ll use Linux commands to configure authorization.

Authorization is the concept of granting access to specific resources in a system. It's important because without authorization any user could access and modify all files belonging to other users or system files. This would certainly be a security risk.

In Linux, file and directory permissions are used to specify who has access to specific files and directories. You’ll explore file and directory permissions and change the ownership of a file and a directory to limit who can access them.

As a security analyst, setting appropriate access permissions is critical to protecting sensitive information and maintaining the overall security of a system.
- Reviewed file permissions using symbolic and numeric notation  
- Modified access using `chmod` for user, group, and others  
- Inspected hidden files and their permission strings  
- Interpreted directory access bits using `ls -ld`  

---

## Linux File Permissions — Manage Access and Ownership

This report was completed as part of the Google Cybersecurity Certificate. It documents the use of Linux commands to inspect, interpret, and modify file permissions. Understanding access rights and enforcing proper ownership is key to maintaining secure system environments.

## My Contributions

- **Check permissions and ownership**
  - Ran `ls -l` and `ls -la` to inspect access control and ownership details  
  - Identified read/write/execute rights across user, group, and other roles  
  - Interpreted symbolic permission strings (e.g., `-rw-r--r--`) and file types (`-`, `d`)

- **Use `chmod` to modify permissions**
  - Applied numeric mode `chmod 640 filename.txt` to set `rw- r-- ---`  
  - Used symbolic mode `chmod o+w filename.txt` to grant write access to others  
  - Verified changes with `ls -l` output comparison

- **Restrict access to sensitive files**
  - Removed execute permissions with `chmod g-x` or `chmod o-x` as needed  
  - Ensured least privilege by locking down hidden logs and project files

- **Check and modify directory permissions**
  - Used `ls -ld` to review access on folders  
  - Applied `chmod 750 foldername/` to set secure directory access  
  - Confirmed directory permissions reflect correct role-based access

---

## Tools Used

- `ls -l` / `ls -la` — to inspect file and hidden file permissions  
- `chmod` — to apply and modify access rights  
- `ls -ld` — to view directory-level access flags  
- `touch`, `nano` — to create and edit files for permission testing  

---

## Reflections

- Using `chmod` in symbolic and numeric mode helps reinforce how binary access maps to privilege levels.  
- Reviewing permission strings builds muscle memory for reading Linux file metadata quickly.  
- Editing hidden file and directory access supports secure configuration management in multi-user systems.
