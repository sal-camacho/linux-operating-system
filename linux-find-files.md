# Activity Overview
You learned about Linux and how to communicate with the OS through the shell. You also learned how to use some of the core commands to navigate the Linux file system and read content from files it contains.

These are essential skills. For example, when investigating unauthorized access, you might navigate to and then read a user access report.

In this lab activity, you’ll navigate a Linux file structure, locate files, and read the contents of files. You’ll also need to answer a few multiple-choice questions based on the information contained in these files.

As a security analyst, it’s key that you know how to navigate, manage, and analyze files remotely via a Linux shell without a graphical user interface.
- Navigated a Linux shell environment to locate and review specific files
- Used commands to display directories, change paths, and read content
- Practiced working without a GUI, simulating remote file management
- Confirmed file contents and interpreted log details from structured outputs

---

# Linux File Navigation — Find Files with CLI Commands Lab

This report was completed as part of the Google Cybersecurity Certificate. It documents how to use foundational Linux commands to navigate file structures, locate and read file contents, and analyze shell output. As a security analyst, the ability to interact with remote systems via Bash is essential for performing investigations and routine analysis tasks.

## My Contributions

- **Step 1: Get the current directory information**
  - Used `pwd` to confirm the current working directory is `/home/analyst`
  - Used `ls` to list directory contents: `logs`, `projects`, `reports`, `temp`

- **Step 2: Change directory and list the subdirectories**
  - Used both relative (`cd reports`) and absolute (`cd /home/analyst/reports`) paths
  - Verified the subdirectory `users` exists within the `reports` folder

- **Step 3: Locate and read the contents of a file**
  - Navigated to `/home/analyst/reports/users`
  - Used `cat Q1_added_users.txt` to review user information
  - Verified employee `aezra` works in Human Resources
  - Identified employee ID `1104` for user `mreed` in IT

- **Step 4: Navigate to a directory and locate a file**
  - Moved to `/home/analyst/logs`
  - Used `ls` to find `server_logs.txt`
  - Used `head server_logs.txt` to view the first 10 lines
  - Identified 3 warning messages in the initial output

---

## Tools Used

- `pwd` — to print the current working directory
- `ls` — to list files and folders in a directory
- `cd` — to navigate between directories
- `cat` — to display full contents of a file
- `head` — to preview the beginning of a file

---

## Reflections

- Practicing navigation and file reading strengthens command-line awareness
- Using relative vs. absolute paths provides flexibility when working across systems
- Reading logs and user files in plain-text prepares for deeper incident response work

---
