# Active Directory Hardening Lab - TryHackMe

## Overview
This project focuses on securing and hardening an Active Directory (AD) environment against common threats and vulnerabilities. By completing this lab, I gained hands-on experience in implementing security best practices and protecting AD from potential attacks.

## Key Learnings

### 1. Vulnerability Mitigation
- **Password Policies**: Implemented strong password policies and account lockout mechanisms to reduce the risk of brute force attacks.
- **User Privileges**: Limited administrative privileges to reduce the attack surface and implemented the principle of least privilege.

### 2. Security Enhancements
- **Group Policy Management**: Configured Group Policies to enforce security settings across the domain, including disabling unnecessary services and blocking vulnerable protocols.
- **Audit and Monitoring**: Set up logging and auditing for critical events, such as unauthorized access attempts, to maintain visibility over AD activities.

### 3. Defensive Techniques
- **Active Directory Tiering**: Segregated network access based on user roles and system criticality, implementing a tiered access model to reduce lateral movement risks.
- **Kerberos and NTLM Hardening**: Strengthened authentication protocols by enforcing Kerberos-only authentication and disabling weak NTLM protocols.

### 4. Threat Detection
- **Analyzing Attack Vectors**: Gained insights into how attackers exploit misconfigurations in AD and how to detect such attempts using SIEM tools.
- **Incident Response**: Developed response strategies for potential AD breaches, focusing on containment and recovery.

## Tools and Technologies
- **Windows Server**: AD domain controller management and configuration.
- **PowerShell**: Scripting for automation of security tasks.
- **Group Policy Editor**: Centralized management of security policies.
- **Event Viewer**: Monitoring and analyzing security logs.

## Conclusion
This lab reinforced the critical importance of securing Active Directory environments, highlighting how proactive measures can prevent breaches and protect sensitive information. The knowledge gained from this lab is essential for any cybersecurity professional working with Windows environments.

