# Cybersecurity-capstone-project
Documentation of my cybersecurity capstone project , including methodology , security analysis, findings , and recommendations.
# Vulnerability Assessment Capstone Project 🔐
## Project Overview
This project documents vulnerability assessment activities completed as part of my cybersecurity capstone training at TS Academy.
The assessment involved identifying and documenting security weaknesses in vulnerable lab environments, including Kioptrix and Metasploitable 2.
The project focused on understanding vulnerabilities, evaluating their potential security impact, and recommending appropriate remediation measures.
## Project Objectives
- Identify and document security vulnerabilities in lab environments.
- Understand vulnerability severity and potential impact.
- Assess the risks associated with exposed services and insecure configurations.
- Recommend practical remediation measures.
- Develop technical reporting and cybersecurity documentation skills.
## Lab Environments
- Kioptrix
- Metasploitable 2
## Vulnerabilities Documented
The assessment task included the following findings:
| Vulnerability | Lab Environment | Reported Severity |
|---|---|---|
| OpenSSL weakness | Kioptrix | Medium — 4.3 |
| ICMP timestamp disclosure | Kioptrix | Low — 2.1 |
| Samba vulnerability | Metasploitable 2 | High — 7.5 |
| Unencrypted Telnet | Metasploitable 2 | Medium — 5.9 |
| ICMP timestamp disclosure | Metasploitable 2 | Low — 2.1 |
Severity scores are reproduced from the original task documentation and have not been independently verified.
## Key Security Lessons
### 1. Vulnerable Cryptographic Services
Outdated or vulnerable cryptographic software may weaken the protection of sensitive communications.
### 2. Information Disclosure
ICMP timestamp responses can reveal information about a system's clock, potentially assisting further reconnaissance.
### 3. Insecure File-Sharing Services
Vulnerabilities in file-sharing services may expose systems to unauthorised access or other security risks, depending on the specific flaw and configuration.
### 4. Unencrypted Remote Access
Telnet does not encrypt its communications. Credentials and other transmitted information may be exposed to someone able to capture the traffic.
## General Remediation Recommendations
- Identify affected software versions and apply appropriate security updates.
- Disable unnecessary services and restrict access to required services.
- Replace Telnet with SSH for secure remote administration.
- Review and securely configure file-sharing services.
- Restrict unnecessary ICMP responses where appropriate.
- Reassess affected systems after remediation to confirm that the weaknesses have been addressed.
## Skills Developed
- Vulnerability documentation
- Risk and severity analysis
- Security assessment reporting
- Linux lab environments
- Remediation planning
- Technical communication
## Conclusion
This project strengthened my understanding of vulnerability assessment, service exposure, security risks, and remediation planning.
It also reinforced the importance of documenting findings clearly and recommending security improvements based on evidence.
---
https://github.com/janetijeomannaemeka/Cybersecurity-capstone-project/blob/main/capstone%20screenshot.jpeg?raw=true
