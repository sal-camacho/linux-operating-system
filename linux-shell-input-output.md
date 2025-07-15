# Activity Overview

When you communicate with the shell, the commands in the shell can take input and return output or error messages.

In this lab activity, you’ll use the echo command to examine how input is received and how output is returned in the shell. Next, you’ll use the expr command to further explore input and output while performing some basic calculations in the shell.

This activity will build foundations in understanding how you communicate with the Linux operating system through the shell. As a security analyst, you'll need to input commands into the shell and recognize when the shell returns either output or an error message.

- Performed basic input/output operations using the Bash shell
- Generated string output with `echo`
- Completed integer-based calculations using `expr`
- Cleared terminal output using the `clear` command
- Explored shell syntax, spacing rules, and integer calculation behavior

---

## Linux Shell Input and Output — Bash Commands

This report was completed as part of the Google Cybersecurity Certificate. It explores how to generate and interpret input/output in a Linux Bash shell using foundational CLI commands. The activity uses `echo`, `expr`, and `clear` to demonstrate how users interact with the operating system at the shell level.

## My Contributions

- **Used `echo` to produce output**
  - Ran `echo hello` and `echo "hello"` to test raw vs. quoted output
  - Confirmed that quoting preserves grouped strings
  - Executed `echo "Sal"` to return custom name output

- **Performed basic calculations using `expr`**
  - Ran `expr 32 - 8` to simulate false-positive alert deduction
  - Ran `expr 3500 * 12` to estimate annual login attempts
  - Confirmed results reflected correct integer output with spacing rules

- **Cleared the Bash shell using `clear`**
  - Ran `clear` to reset the shell view and remove previous input/output

- **Explored command behavior further (optional task)**
  - Executed additional `echo` and `expr` examples using alternate inputs
  - Verified that fractional math is unsupported and spacing is mandatory

---

## Tools Used

- `echo` — for string output
- `expr` — for basic integer arithmetic
- `clear` — to reset shell display

---

## Reflections

- Practiced core Bash functionality for working with system communication.
- Gained confidence using shell commands to validate input and structure outputs.
- Built foundational skills applicable to more advanced Linux scripting, automation, and incident investigation.
