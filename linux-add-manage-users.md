# Activity Overview
In this activity, you’ll use Linux commands to configure authorization.

Authorization is the concept of granting access to specific resources in a system. It's important because without authorization any user could access and modify all files belonging to other users or system files. This would certainly be a security risk.

In Linux, file and directory permissions are used to specify who has access to specific files and directories. You’ll explore file and directory permissions and change the ownership of a file and a directory to limit who can access them.

As a security analyst, setting appropriate access permissions is critical to protecting sensitive information and maintaining the overall security of a system.
- Created a new user account with a home directory  
- Changed file ownership to assign access rights  
- Added the user to a new group for role-based access  
- Removed the user and verified cleanup  

---

## Linux User Management — Add, Modify, and Remove Accounts

This report was completed as part of the Google Cybersecurity Certificate. It documents how to manage user accounts in Linux using Bash commands. These tasks are essential for authentication workflows, access control, and secure system administration.

## My Contributions

- **Add a new employee**
  - Used `useradd` with `-m` and `-d` flags to create a home directory  
  - Verified account creation using `ls /home` and `cat /etc/passwd`

- **Change ownership of a file**
  - Applied `chown` to assign file ownership to the new user  
  - Confirmed changes using `ls -l` on the target file

- **Add the new employee to a new group**
  - Created a group using `groupadd`  
  - Added the user with `usermod -aG`  
  - Verified group membership using `groups`

- **Delete the employee from the system**
  - Used `userdel -r` to remove the account and home directory  
  - Verified deletion using `cat /etc/passwd` and `ls /home`

---

## Tools Used

- `useradd` — to create new user accounts  
- `chown` — to assign file ownership  
- `groupadd` / `usermod` — to manage group membership  
- `userdel` — to remove accounts and directories  

---

## Reflections

- Creating users with home directories ensures proper workspace setup.  
- Assigning ownership with `chown` reinforces access control and accountability.  
- Group management supports role-based access and privilege separation.  
- Removing users cleanly prevents orphaned files and access risks.
