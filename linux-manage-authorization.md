# Activity Overview
In this activity, you’ll use Linux commands to configure authorization.

Authorization is the concept of granting access to specific resources in a system. It's important because without authorization any user could access and modify all files belonging to other users or system files. This would certainly be a security risk.

In Linux, file and directory permissions are used to specify who has access to specific files and directories. You’ll explore file and directory permissions and change the ownership of a file and a directory to limit who can access them.

As a security analyst, setting appropriate access permissions is critical to protecting sensitive information and maintaining the overall security of a system.
- Checked file and directory permissions using `ls -l`  
- Identified incorrect or insecure permission settings  
- Changed file access levels using `chmod`  
- Removed unauthorized access using ownership and permission flags  

---

## Linux Authorization Management — File Permissions and Access Control

This report was completed as part of the Google Cybersecurity Certificate. It documents how to examine and manage Linux file permissions to ensure authorized access and secure file handling. You’ll apply CLI-based permission controls that are essential for system auditing and user account protection.

## My Contributions

- **Step 1: Check permissions for files in a directory**  
  - Used `ls -l` to list permission settings, file types, owners, and group associations  
  - Reviewed access levels for critical files and directories in `/home/analyst`

- **Step 2: Change file permissions**  
  - Identified files with insecure permissions (e.g., world-writable or executable when not needed)  
  - Applied `chmod` commands to correct read, write, and execute settings for secure access

- **Step 3: Remove unauthorized access from directories**  
  - Used `chmod` to strip group/world access on sensitive directories  
  - Verified permission changes using `ls -ld` and ensured secure directory setup

---

## Tools Used

- `ls -l` — to view file permissions and ownership  
- `chmod` — to modify access rights and enforce least privilege  
- `ls -ld` — to inspect directory-level permission attributes  

---

## Reflections

- Managing permissions reinforces the importance of least privilege principles in system administration.  
- Using `chmod` gives fine-tuned control over who can read, write, or execute files.  
- Reviewing permissions prepares analysts for authorization audits, misconfig detection, and secure system setups.
