# Elevate-Labs-T3 - Perform a basic vulnerability scan.

## Original Plan  
The task suggested using **OpenVAS Community Edition** or **Nessus Essentials** for vulnerability scanning.  
- OpenVAS did not run properly on my Windows system despite attempts via WSL and Docker.  
- Nessus Essentials installer failed on my machine due to compatibility issues.

## Alternative Tool Used  
I chose to use **chkrootkit**, a free and open-source Linux tool that detects rootkits and some common vulnerabilities.  
It runs on Windows Subsystem for Linux (WSL).

