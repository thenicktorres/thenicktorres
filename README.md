### Hey, I'm Nick 👋

I'm a 4th-year Computer Science student at UGA focused on **Cybersecurity**. I like building things that detect threats, investigate incidents, and breaking into systems so developers can make them harder to break.

🎯 **Currently seeking internships** in Cybersecurity.

---

### 🧰 What I work with

**Languages:** Python · Java · SQL · C/C++ 

**Security & Forensics:** Microsoft Sentinel · Wireshark · VirusTotal · MITRE ATT&CK · Splunk · Nmap · Metasploit

**Operating Systems:** Linux, macOS, Windows, Unix

**Cloud / Virtualization:** AWS, Microsoft Azure, VMware 


## 👨‍💻 Projects I'm proud of

### [🛰 Azure Sentinel Live Attack Map](https://github.com/thenicktorres/honeypot-script-for-azure-sentinel-map)
Deployed a honeypot on Azure and built a SIEM workflow in Microsoft Sentinel to visualize live RDP brute-force attacks geographically. PowerShell automation enriches failed login events with attacker IP geolocation before forwarding to Log Analytics.  
**Stack:** Azure, Microsoft Sentinel, PowerShell, KQL


### [🔐 Password Manager with SHA-256](https://github.com/thenicktorres/Password-Generator-Manager-w-SHA-256)
A local password manager and generator that hashes credentials with SHA-256 and stores them in an encrypted vault. Built to learn how real password managers handle secrets at rest.  
**Stack:** Python, cryptography


### [🌐 Web Application Security Scanner](https://github.com/thenicktorres/Simple-Web-Application-Security-Scanner-with-Python)
Python tool that scans web apps for common vulnerabilities — SQL injection, XSS, open ports, missing security headers. Generates a readable report for each target.  
**Stack:** Python, requests, BeautifulSoup


### [📊 Security Log Analyzer](https://github.com/thenicktorres/security-log-analyzer)
Parses and analyzes security logs to surface suspicious patterns — Built to practice the kind of triage work a SOC analyst does daily.  
**Stack:** Python

---

### 🕵️ Blue Team CTFs

Completed 6 blue team challenges on [CyberDefenders](https://cyberdefenders.org/) across forensics and threat intel:

- **[WebStrike](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/thenicktorres/webstrike/)** — Network forensics. Analyzed a PCAP in Wireshark to trace a web server compromise: identified the attacker's geolocation and User-Agent, the malicious web shell uploaded, the upload directory, the reverse shell port, and the file targeted for exfiltration.
- **[Oski](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/thenicktorres/oski/)** — Threat intel. Investigated a Stealc malware sample delivered via a malicious PPT using ANY.RUN and VirusTotal — extracted the C2 server, RC4 decryption key, and mapped the credential-theft behavior to MITRE ATT&CK.
- **[Poisoned Credentials](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/thenicktorres/poisonedcredentials/)** — Network forensics. Investigated an LLMNR/NBT-NS poisoning attack in Wireshark to identify the rogue machine, the affected hosts that received poisoned responses, the compromised user account, and the SMB host the attacker pivoted to.
- **[Yellow RAT](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/thenicktorres/yellow-rat/)** — Threat intel. Used VirusTotal to identify a malware family causing search-redirect traffic — pulled the common filename, compilation timestamp, dropped `.dat` payload in AppData, and the C2 server the sample was beaconing to.
- **[Amadey](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/thenicktorres/amadey/)** — Endpoint forensics. Analyzed a memory dump with Volatility 3 to reconstruct an Amadey Trojan infection: traced the parent process, located its on-disk path, identified the C2 IP, recovered dropped payloads, and uncovered the persistence mechanism.
- **[L'espion](https://cyberdefenders.org/blueteam-ctf-challenges/achievements/thenicktorres/lespion/)** — Threat intel / OSINT. Investigated an insider threat by pivoting from a leaked GitHub repo (exposed API key, base64-encoded credentials, an XMRig miner) through social media and reverse image search to track the insider's movements and identify the company's location.


---


### 📫 Get in touch

- **LinkedIn:** https://www.linkedin.com/in/nick-torres11/
- **Email:** nicktorres.work@gmail.com
---
