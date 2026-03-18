
# Memory Forensics Investigation – Volatility 3

This project presents a memory forensics investigation conducted using Volatility 3 to identify malicious activity and analyze a compromised system.

## Overview
The investigation focuses on analyzing a Windows memory dump to detect suspicious processes, uncover attacker behavior, and determine the scope of compromise.

## Tools Used
- Volatility 3  
- VirusTotal  

## Key Findings
- Identified a malicious PowerShell process  
- Detected hidden execution using command-line arguments  
- Discovered second-stage payload (3435.dll)  
- Found remote shared directory access (davwwwroot)  
- Identified malware family: Strelastealer  
- Mapped activity to MITRE ATT&CK T1218.011  

## Report
📄 Full analysis available in:Volatility 3.pdf 

Source Lab:https://cyberdefenders.org/blueteam-ctf-challenges/reveal/

---

📌 This project demonstrates practical skills in memory forensics, malware analysis, and incident response.
