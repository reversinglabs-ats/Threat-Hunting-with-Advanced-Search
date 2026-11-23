# Spectra Analyze Advanced Search


## Table of Contents

- [About this document and Conventions](<00 Front Matter.md>)

### Part 1: Reference and Methodology

- [1.1  Advanced Search Syntax Quick Reference](<01 Reference and Methodology/01.01 Advanced Search Syntax Quick Reference.md>)
- [1.2  ATT&CK Coverage](<01 Reference and Methodology/01.02 ATT&CK Coverage.md>)
- [1.3  Triage, False-Positive Reduction and Detection Gaps](<01 Reference and Methodology/01.03 Triage, False-Positive Reduction and Detection Gaps.md>)
- [1.4  Recency and Time-Based Hunting](<01 Reference and Methodology/01.04 Recency and Time-Based Hunting.md>)
- [1.5  Submitters and Ingest Sources](<01 Reference and Methodology/01.05 Submitters and Ingest Sources.md>)

### Part 2: Network Protocols and Infrastructure

- [2.1  DNS, Encrypted DNS and Domain Impersonation](<02 Network Protocols and Infrastructure/02.01 DNS, Encrypted DNS and Domain Impersonation.md>)
- [2.2  Internet Protocol Address (IPv4)](<02 Network Protocols and Infrastructure/02.02 Internet Protocol Address (IPv4).md>)
- [2.3  Application Layer Protocols and Non-Standard Ports](<02 Network Protocols and Infrastructure/02.03 Application Layer Protocols and Non-Standard Ports.md>)

### Part 3: Encryption, Certificates and Fingerprinting

- [3.1  TLS and Fingerprinting](<03 Encryption, Certificates and Fingerprinting/03.01 TLS and Fingerprinting.md>)
- [3.2  Code Signing Abuse](<03 Encryption, Certificates and Fingerprinting/03.02 Code Signing Abuse.md>)

### Part 4: Identity, Directory and Email

- [4.1  LDAP, Active Directory and Group Policy](<04 Identity, Directory and Email/04.01 LDAP, Active Directory and Group Policy.md>)
- [4.2  Azure Entra and Cloud Identity](<04 Identity, Directory and Email/04.02 Azure Entra and Cloud Identity.md>)
- [4.3  Email and Phishing](<04 Identity, Directory and Email/04.03 Email and Phishing.md>)

### Part 5: Remote Access and Lateral Movement

- [5.1  Server Message Block (SMB) and PsExec](<05 Remote Access and Lateral Movement/05.01 Server Message Block (SMB) and PsExec.md>)
- [5.2  Remote Desktop Protocol (RDP)](<05 Remote Access and Lateral Movement/05.02 Remote Desktop Protocol (RDP).md>)
- [5.3  Secure Shell (SSH)](<05 Remote Access and Lateral Movement/05.03 Secure Shell (SSH).md>)
- [5.4  Windows Remote Management (WinRM)](<05 Remote Access and Lateral Movement/05.04 Windows Remote Management (WinRM).md>)
- [5.5  Remote Management and Monitoring Tools](<05 Remote Access and Lateral Movement/05.05 Remote Management and Monitoring Tools.md>)
- [5.6  Remote File Copy](<05 Remote Access and Lateral Movement/05.06 Remote File Copy.md>)
- [5.7  Credential Dumping Tools](<05 Remote Access and Lateral Movement/05.07 Credential Dumping Tools.md>)
- [5.8  Sysinternals Usage](<05 Remote Access and Lateral Movement/05.08 Sysinternals Usage.md>)
- [5.9  Network Scanners](<05 Remote Access and Lateral Movement/05.09 Network Scanners.md>)

### Part 6: Command and Control and Network Behavior

- [6.1  Command and Control and Beaconing](<06 Command and Control and Network Behavior/06.01 Command and Control and Beaconing.md>)
- [6.2  Anonymization and Tunneling Tools](<06 Command and Control and Network Behavior/06.02 Anonymization and Tunneling Tools.md>)

### Part 7: Collection, Staging and Exfiltration

- [7.1  Archive Staging](<07 Collection, Staging and Exfiltration/07.01 Archive Staging.md>)
- [7.2  Transfer and Exfiltration Tools](<07 Collection, Staging and Exfiltration/07.02 Transfer and Exfiltration Tools.md>)
- [7.3  Exfiltration to Web Services](<07 Collection, Staging and Exfiltration/07.03 Exfiltration to Web Services.md>)

### Part 8: Malware Analysis and Tooling

- [8.1  File Analysis](<08 Malware Analysis and Tooling/08.01 File Analysis.md>)
- [8.2  Documents and Image Metadata](<08 Malware Analysis and Tooling/08.02 Documents and Image Metadata.md>)
- [8.3  Packers & Obfuscation](<08 Malware Analysis and Tooling/08.03 Packers & Obfuscation.md>)
- [8.4  Malware Clustering, Pivoting and Build Fingerprints](<08 Malware Analysis and Tooling/08.04 Malware Clustering, Pivoting and Build Fingerprints.md>)
- [8.5  Ransomware](<08 Malware Analysis and Tooling/08.05 Ransomware.md>)
- [8.6  Infostealers](<08 Malware Analysis and Tooling/08.06 Infostealers.md>)
- [8.7  .NET Malware](<08 Malware Analysis and Tooling/08.07 .NET Malware.md>)
- [8.8  Linux & macOS Malware](<08 Malware Analysis and Tooling/08.08 Linux & macOS Malware.md>)
- [8.9  Mobile Malware and Browser Extensions](<08 Malware Analysis and Tooling/08.09 Mobile Malware and Browser Extensions.md>)
- [8.10  Supply Chain and Vulnerable Components](<08 Malware Analysis and Tooling/08.10 Supply Chain and Vulnerable Components.md>)
- [8.11  Malware Types by Detection Name](<08 Malware Analysis and Tooling/08.11 Malware Types by Detection Name.md>)
- [8.12  Spectra Core Tags and Indicators](<08 Malware Analysis and Tooling/08.12 Spectra Core Tags and Indicators.md>)
- [8.13  Boot, Firmware, WebAssembly and Package Malware](<08 Malware Analysis and Tooling/08.13 Boot, Firmware, WebAssembly and Package Malware.md>)

### Part 9: Web Application and Server-Side Threats

- [9.1  Web Shells and Server-Side Compromise](<09 Web Application and Server-Side Threats/09.01 Web Shells and Server-Side Compromise.md>)
- [9.2  Server Side Request Forgery (SSRF)](<09 Web Application and Server-Side Threats/09.02 Server Side Request Forgery (SSRF).md>)
- [9.3  Web Services, WordPress and XML-RPC](<09 Web Application and Server-Side Threats/09.03 Web Services, WordPress and XML-RPC.md>)

### Part 10: Endpoint Execution, Persistence and Evasion

- [10.1  Initial Access Delivery](<10 Endpoint Execution, Persistence and Evasion/10.01 Initial Access Delivery.md>)
- [10.2  Executable Downloads and Remote Fetches](<10 Endpoint Execution, Persistence and Evasion/10.02 Executable Downloads and Remote Fetches.md>)
- [10.3  Masquerading and Binary Evasion](<10 Endpoint Execution, Persistence and Evasion/10.03 Masquerading and Binary Evasion.md>)
- [10.4  Execution and Persistence](<10 Endpoint Execution, Persistence and Evasion/10.04 Execution and Persistence.md>)
- [10.5  Privilege Escalation and Defense Impairment](<10 Endpoint Execution, Persistence and Evasion/10.05 Privilege Escalation and Defense Impairment.md>)
