# Elevate-Labs-T3 - Perform a basic vulnerability scan.

## Original Plan  
The task suggested using **OpenVAS Community Edition** or **Nessus Essentials** for vulnerability scanning.  
- OpenVAS did not run properly on my Windows system despite attempts via WSL and Docker.  
- Nessus Essentials installer failed on my machine due to compatibility issues.

## Alternative Tool Used  
I chose to use **chkrootkit**, a free and open-source Linux tool that detects rootkits and some common vulnerabilities.  
It runs on Windows Subsystem for Linux (WSL).

## Observations:

I performed a vulnerability scan on my system using chkrootkit via WSL. The scan checked for over 70 known rootkits and suspicious system behavior. No rootkits or infections were found, and key system binaries like ps, ls, login, and cron were marked clean or not found (expected in WSL). A few warnings were raised about .gitignore files in Python package directories and potential sniffers, but analysis showed these are false positives.

The screenshots are added in the file: **Task3.pdf**
