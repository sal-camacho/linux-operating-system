# Activity Overview
In this activity, you’ll use the useradd, usermod, userdel, and chown commands to manage user access in the Linux Bash shell.
Previously, you focused on authorization, the concept of granting access to specific resources in a system. Another important concept in security is authentication. Authentication is the process of a user proving that they are who they say they are in the system.

When managing this, security analysts need to ensure:

- not all users get access to the system,
- new users (those who are new to the organization or a group) are added to the system, and
- current users who change groups or leave the organization are deleted from the system.

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
