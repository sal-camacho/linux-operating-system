# Activity Overview
In this activity, you’ll use the grep command and piping to search for files and to return specific information from files.

As a security analyst, it’s key to know how to find the information you need. The ability to search for specific strings can help you locate what you need more efficiently.
- Searched for specific error messages within system log files  
- Used `grep` to match string patterns and filter output  
- Applied piping (`|`) to combine commands and refine results  
- Practiced reading log entries and identifying user activity and security-related data  

---

## Linux Command Filtering — `grep` and Pipe Operator

This report was completed as part of the Google Cybersecurity Certificate. It documents how to filter output in the Bash shell using the `grep` command alongside the pipe (`|`) operator. These tools are essential for streamlining log analysis, extracting meaningful patterns, and investigating system activity across text files.

## My Contributions

- **Search for error messages in a file**
  - Used `grep "error"` to locate entries containing system error reports
  - Applied case-sensitive search to filter relevant alerts for review

- **Search for files that contain a specific string**
  - Ran recursive search across directories to locate files referencing usernames or warnings
  - Verified results using exact match flags and path inspection

- **Search for information in user files**
  - Identified employee data based on department or role keywords
  - Filtered structured files containing user credentials and job titles using targeted string search

---

## Tools Used

- `grep` — pattern matching and output filtering  
- `|` (pipe) — passed results from one command into `grep`  
- `cat`, `ls`, `head` — to display and validate file contents prior to filtering  

---

## Reflections

- Filtering with `grep` allows for fast log parsing and pattern recognition.
- Piping outputs enhances workflow efficiency when managing large text files.
- These tools directly support security analysis tasks like error tracking, alert validation, and user account auditing.
