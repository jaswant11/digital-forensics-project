# digital-forensics-project
Exploration of open-source forensic tools (Recuva, Browser History Capturer, Volatility 3) for file recovery, browser analysis, and memory dump analysis

# Open-Source Digital Forensic Tools Project

This project was completed as part of **INFO 2411: Foundations of Computer Security** at Kwantlen Polytechnic University.  
It explores the use of open-source forensic tools to perform hands-on investigations in areas such as file recovery, browser history analysis, and memory forensics.

---

## Project Overview
The goal of this project was to gain practical experience with tools used in digital investigations and cybersecurity incident response.  
We focused on three key forensic areas:

1. **File Recovery** – Using Recuva to recover deleted files from a formatted partition.  
2. **Browser Forensics** – Using Browser History Capturer (BHC) to extract browser artifacts (visited sites, bookmarks, timestamps).  
3. **Memory Forensics** – Using WinPmem and Volatility 3 to capture and analyze system RAM, identify running processes, command-line arguments, and scan for in-memory malware.

---

## Tools and Technologies
- Recuva – File recovery and disk analysis  
- Browser History Capturer (BHC) – Web browser artifact extraction  
- Volatility 3 – Memory dump analysis  
- WinPmem – Memory acquisition tool for Windows 10  
- Windows 10 Test Environment  

---

## Key Tasks
- Simulated accidental file deletion and successfully recovered files using Recuva.  
- Extracted browsing history and analyzed user activity with BHC.  
- Acquired a live memory dump with WinPmem and analyzed it using Volatility 3 plugins:  
  - `windows.pslist` (active processes)  
  - `windows.cmdline` (command-line arguments)  
  - `windows.malfind` (malware injection scan)  
  - `windows.netscan` (network connections)  
- Verified system state and confirmed absence of malicious processes or network activity.  

---

## Results and Learnings
- Gained hands-on experience with forensic tools used in real-world investigations.  
- Learned how volatile memory analysis can detect fileless malware and hidden processes missed by traditional disk forensics.  
- Understood limitations of recovery tools (for example, overwritten data cannot be retrieved).  
- Strengthened skills in digital evidence handling, command-line usage, and technical documentation.
- 
## **DOCUMENTATION**
The original report is attached in this repository with screenshots.
---

## Team
- Jaswant Singh – Memory Dump Analysis (Volatility 3, WinPmem)  
- Pasang Sherpa – File Recovery (Recuva, Autopsy, Sleuth Kit)  
- Phi Tien Tran – Browser History Forensics (BHC)  

---

## Relevance to Cybersecurity
This project demonstrates practical application of digital forensic techniques in:  
- Incident response  
- Malware analysis  
- Cybercrime investigations  

It highlights how open-source tools can provide accessible, cost-effective solutions for training and professional use.

