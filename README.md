# Open Source Audit Project

## Overview
This project is a detailed audit and analysis of the Apache HTTP Server as part of the OSS NGMC course. It covers the origin, philosophy, licensing, ecosystem, and practical usage of Apache on a Linux system.

The report also includes multiple shell scripts demonstrating basic Linux automation and system analysis.

---

## Objectives
- Understand the concept of open-source software  
- Study the development and impact of Apache HTTP Server  
- Explore licensing models like Apache License, GPL, and MIT  
- Analyze how Apache works on a Linux system  
- Implement shell scripts for practical understanding  

---

## Topics Covered

### Part A — Origin and Philosophy
- Problem Apache was created to solve  
- History and development  
- Open-source philosophy  
- Ethical considerations  

### Part B — Linux Footprint
- Installation using APT  
- Key directories (/etc/apache2, /var/log/apache2)  
- Service management using systemctl  
- Update mechanism  

### Part C — FOSS Ecosystem
- Dependencies and modules  
- Role in LAMP stack (Linux, Apache, MySQL, PHP)  
- Impact on modern web development  

### Part D — Comparison
- Apache vs Proprietary software (Microsoft IIS)  
- Cost, security, control, and flexibility  

---

## Shell Scripts Included

### Script 1 — System Identity Report
Displays system details such as:
- Kernel version  
- Username  
- Uptime  
- Date and time  

### Script 2 — FOSS Package Inspector
- Checks if a package (such as Apache) is installed  
- Displays package information  
- Uses conditional logic and case statements  

### Script 3 — Disk and Permission Auditor
- Analyzes important directories  
- Shows disk usage and permissions  
- Uses loops and command-line tools  

### Script 4 — Log File Analyzer
- Reads log files  
- Counts keyword occurrences (default: error)  
- Useful for basic security analysis  

### Script 5 — Open Source Manifesto Generator
- Takes user input  
- Generates a custom open-source statement  
- Saves output to a file  

---

## How to Run Scripts

chmod +x script_name.sh  
./script_name.sh  

Example:
./script4.sh logfile.txt error  

---

## Requirements
- Linux (Ubuntu or Debian recommended)  
- Bash shell  
- Apache installed (sudo apt install apache2)  

---

## References
- GNU Project  
- Open Source Initiative  
- Apache Documentation  
- Linux Manual Pages  

---

## Conclusion
This project helped in understanding how open-source software works in real-world scenarios. Apache HTTP Server is a strong example of collaborative development and plays an important role in modern web infrastructure.

---

## Author
Aditya Das  
Registration No: 24BCE10335  