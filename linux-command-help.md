# Activity Overview
As a security analyst, you won’t have all the answers all the time, but you can learn where to find them. One of the great things about Linux is that you can get help right through the command line.

In this activity, you’ll use the man and whatis commands to get information on other commands and how they work. You’ll also use the apropos command to search the manual page for a command with a specified string.

When working as a security analyst, you'll likely find it useful to know how to discover which command to use or information about what commands do.

- Used `man` to read manual pages for Linux commands  
- Applied `whatis` to get short command descriptions  
- Used `apropos` to search for commands by keyword  
- Compared commands and identified options for group creation  

---

# Linux Command Help — Using man, whatis, and apropos

This report was completed as part of the Google Cybersecurity Certificate. It documents how to use built-in Linux tools to explore command usage, syntax, and options. These skills are essential for troubleshooting, learning new commands, and working independently in CLI environments.

## My Contributions

- **Use `man` to explore command options**
  - Ran `man useradd` and `man groupadd` to review syntax and flags  
  - Navigated manual pages using arrow keys and `/search`  
  - Verified usage examples and default behaviors

- **Use `whatis` to get command summaries**
  - Ran `whatis chmod`, `whatis passwd`, and `whatis nano`  
  - Compared short descriptions to confirm command purpose

- **Use `apropos` to search by keyword**
  - Ran `apropos group` to find commands related to group management  
  - Identified `groupadd`, `groupdel`, and `groupmod` as relevant tools

- **Compare commands and find options**
  - Compared `useradd` vs. `adduser` using `man` and `whatis`  
  - Identified differences in syntax and default behavior  
  - Verified that `groupadd` is the correct command to create a new group

---

## Tools Used

- `man` — to read full manual pages for commands  
- `whatis` — to get brief command descriptions  
- `apropos` — to search for commands by keyword  
- `/search` — to locate specific flags or terms inside `man` pages  

---

## Reflections

- Knowing how to use `man`, `whatis`, and `apropos` builds independence in CLI environments.  
- These tools help analysts troubleshoot, verify syntax, and explore unfamiliar commands.  
- Searching by keyword supports faster discovery of relevant tools during investigations.
