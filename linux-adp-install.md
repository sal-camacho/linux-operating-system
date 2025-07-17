# Activity Overview
In this activity, you’ll use the Advanced Package Tool (APT) and sudo to install and uninstall applications in a Linux Bash shell.

While installing Linux applications can be a complex task, the APT package manager manages most of this complexity for you and allows you to quickly and reliably manage the applications in a Linux environment.

The virtual machine you access in this lab has a Debian-based distribution of Linux running, and that works with the APT package manager. Using a virtual machine prevents damage to a system in the event its tools are used improperly. It also gives you the ability to revert to a previous state.

As a security analyst, it's likely you'll need to know how to install and manage applications on a Linux operating system.
As a security analyst, you're responsible for ensuring that key network security applications are installed and properly managed. In this activity, you:

- Confirm APT is installed in Bash
-  Install Suricata with APT
- Uninstall Suricata with APT
- Install tcpdump with APT
- Reinstall Suricata with APT
  
---

## Linux Package Management — APT Installation

This report was completed as part of the Google Cybersecurity Certificate. It documents how to install, remove, and verify applications using the Advanced Package Tool (APT) in a Debian-based Linux Bash environment. The activity demonstrates how security analysts use CLI tools to manage software while maintaining a secure operating system.
## My Contributions

- **Verified APT was installed**
  - Ran `apt` and confirmed package manager presence and version.

- **Installed Suricata**
  - Command: `sudo apt install suricata`
  - Verified by running `suricata` and reviewing version and usage output.

- **Uninstalled Suricata**
  - Command: `sudo apt remove suricata`
  - Confirmed removal using `suricata`, which returned an error indicating the binary was missing.

- **Installed tcpdump**
  - Command: `sudo apt install tcpdump`

- **Listed installed applications**
  - Command: `apt list --installed`
  - Verified tcpdump was installed, Suricata was absent (prior to reinstall).

- **Reinstalled Suricata**
  - Command: `sudo apt install suricata`
  - Ran `apt list --installed` again to confirm both Suricata and tcpdump were present.

---

## Tools Used

- Advanced Package Tool (`APT`)
- `sudo` for privileged command execution
- Suricata (network intrusion detection)
- tcpdump (packet sniffer)

---

## Reflections

- Practicing APT commands improved familiarity with package dependencies and install flows.
- Verifying application presence and CLI functionality is critical in secure environments.
- The lab emphasized foundational Linux skills relevant to system administration and incident response.
