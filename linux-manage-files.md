# Activity Overview
In this activity, you’ll use Linux commands to modify a directory structure and the files it contains.

You’ll also use the nano text editor to add text to a file.

You previously learned that directories help you organize subdirectories and files in Linux. As a security analyst, creating, removing, and editing directories and files are core tasks you’ll need to perform to help you to manage data.

When data is well organized, you can more easily detect issues and keep data safe.
- Created new directories and removed unneeded ones  
- Moved and deleted files within the Linux file system  
- Edited file content using `nano` in a text-based interface  
- Practiced proper file hygiene for log management and workspace cleanup  

---

## Linux File Management — Directory and Nano Editing

This report was completed as part of the Google Cybersecurity Certificate. It documents core file operations in a Linux environment including creating, moving, deleting, and modifying files using Bash commands. The activity emphasizes system organization and text manipulation using the `nano` text editor.

## My Contributions

- **Create a new directory**
  - Used `mkdir` to add a new directory for test file storage  
  - Verified creation using `ls` to confirm placement  

- **Remove a directory**
  - Used `rmdir` or `rm -r` to delete test directories after validation  
  - Confirmed removal with a follow-up `ls` check  

- **Move a file and delete a file**
  - Applied `mv` to relocate specific files to target directories  
  - Used `rm` to delete obsolete or test files after review  

- **Create and edit a file with `nano`**
  - Launched `nano` to create a new text file  
  - Added structured content for user activity or configuration notes  
  - Saved file and verified with `cat` to confirm final content  

---

## Tools Used

- `mkdir` — to create new directories  
- `rmdir` / `rm` — to remove directories and files  
- `mv` — to move files between locations  
- `nano` — to edit file content within a shell environment  

---

## Reflections

- Practicing file creation and removal deepens control over Linux workspace organization.  
- Moving files helps simulate log rotation and structured data retention.  
- Using `nano` builds fluency with remote text editing, critical for config and audit work.
