# Task1 - Nmap Network Port Scanning  
Basic Network Reconnaissance using Nmap

 Objective  
Perform a TCP SYN scan on your local network using Nmap to identify open ports and exposed services. Understand how attackers discover network vulnerabilities and assess basic security posture.

 Tools Used  
- Nmap (Network Mapper)  
- Command Prompt (Windows)  
- (Optional) Wireshark  
- Google (for service/port research)

 Steps Performed  
1. Installed Nmap from the official website.  
2. Identified local IP and subnet (e.g., `192.168.1.0/24`).  
3. Ran the Nmap TCP SYN scan:
   bash
   nmap -sS 192.168.1.0/24 -oN scan_result.txt

Files Included
scan_result.txt: Output of the Nmap scan
report.md: Analysis of scan results and associated risks
screenshots/: Screenshot of terminal output or Nmap results
README.md: This file

Submission
This repository is for the Cyber Security Internship - Task 1.

# Author: Suhani Pandey
