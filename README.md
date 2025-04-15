# Home-labs
This repo contains my home lab tests and ctfs challanges documentaion 
## 🛠️ Lab Components
1. **Metasploitable 2**  
   - Weak credential identification (`admin:admin` → SSH compromise)  
   - Service hardening (FTP/SMB misconfigurations → firewall rules)
  
     
2. ## 🖥️ Windows 7 Forensics Exercises  

### Brute Force Detection  
- Analyzed `Security.evtx` logs to identify RDP attack patterns.  
- Created PowerShell script to automate detection.  
- [Full Methodology](/windows7_forensics/brute_force)  

### Malware Hunting  
- Identified persistence mechanisms in registry/Run keys.  
- Detected malicious network traffic with Wireshark.  
- [Artifacts Found](/windows7_forensics/malware_artifacts) 
