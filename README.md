<h1>Cybersecurity Project – Active Directory Attack & Defense</h1>

<h2>Description</h2>

This project documents the expansion, attack simulation, investigation, and defense of an Active Directory environment using Windows Server 2022, Windows 11, and Kali Linux virtual machines. The goal of this project was to gain hands-on experience with common Active Directory attack techniques and understand how these attacks can be identified, investigated, and mitigated.

The project expanded an existing Active Directory environment by configuring domain users, organizational units, security groups, service accounts, Group Policy settings, and security auditing. Controlled Kerberoasting and password spraying attacks were performed using Kali Linux, followed by Windows security event analysis, defensive hardening, and post-remediation verification.

The project is divided into the following phases:
- <b>Phase 1 – Active Directory Environment & Security Configuration</b>
- <b>Phase 2 – Kerberoasting Attack & Defense</b>
- <b>Phase 3 – Password Spraying Attack & Defense</b>

This project provides hands-on experience with both offensive and defensive Active Directory security and will later be integrated with a Splunk SIEM environment for centralized detection and monitoring.

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Command Prompt (CMD)</b>
- <b>Active Directory Domain Services (AD DS)</b>
- <b>Active Directory Users and Computers (ADUC)</b>
- <b>Group Policy Management</b>
- <b>Windows Event Viewer</b>
- <b>Kali Linux</b>
- <b>Impacket</b>
- <b>Hashcat</b>
- <b>NetExec</b>


<h2>Environments Used</h2>

- <b>Virtualization Platform: Oracle VirtualBox</b>
- <b>Host Operating System: Windows 10 / Windows 11</b>
- <b>Domain Controller: Windows Server 2022</b>
- <b>Domain Workstation: Windows 11</b>


<h2>Project Phases:</h2>

<h3>Phase 1 – Active Directory Environment & Security Configuration</h3>

Expanded and configured the existing Active Directory environment to support controlled attack and defense scenarios. Created domain users, organizational units, security groups, and service accounts while configuring Group Policy, permissions, networking, and security auditing.

Topics covered:
- <b>Domain user creation</b>
- <b>Organizational Units (OUs)</b>
- <b>Security groups</b>
- <b>Service accounts</b>
- <b>Group Policy configuration</b>
- <b>User and group permissions</b>
- <b>Windows workstation configuration</b>
- <b>Network configuration</b>
- <b>Security and auditing configuration</b>

<a href="https://github.com/royalexvo/Active-Directory-Attack-Defense-Phase-1.git">View Phase 1 – Active Directory Environment & Security Configuration</a>

<h3>Phase 2 – Kerberoasting Attack & Defense</h3>

Performed a controlled Kerberoasting attack against an Active Directory service account using Impacket and Hashcat. Investigated Kerberos service ticket activity through Windows Security logs, implemented service account hardening, and retested the attack to evaluate the effectiveness of the defensive improvements.

Topics covered:
- <b>Kerberos authentication</b>
- <b>Service Principal Names (SPNs)</b>
- <b>Service accounts</b>
- <b>Kerberoasting attack simulation</b>
- <b>Windows security event analysis</b>
- <b>Attack investigation</b>
- <b>Service account hardening</b>
- <b>Mitigation and remediation</b>
- <b>Post-remediation verification</b>

<a href="https://github.com/royalexvo/Active-Directory-Attack-Defense-Phase-2.git">View Phase 2 – Kerberoasting Attack & Defense</a>

<h3>Phase 3 – Password Spraying Attack & Defense</h3>

Performed a controlled password spraying attack against six Active Directory domain accounts using NetExec. Investigated failed authentication events, developed a PowerShell-based detection method, strengthened password policies and account credentials, and verified the security configuration through post-remediation testing.

Topics covered:
- <b>Password spraying attack simulation</b>
- <b>Domain authentication activity</b>
- <b>Windows logon events</b>
- <b>Failed authentication analysis</b>
- <b>Account lockout policies</b>
- <b>Password policies</b>
- <b>Attack investigation</b>
- <b>Defensive controls</b>
- <b>Remediation and hardening</b>
- <b>Post-remediation verification</b>

<a href="https://github.com/royalexvo/Active-Directory-Attack-Defense-Phase-3.git">View Phase 3 – Password Spraying Attack & Defense</a>

<h2>Skills Developed</h2>

- <b>Active Directory Security</b>
- <b>Active Directory Administration</b>
- <b>Windows Security</b>
- <b>Kerberos Security</b>
- <b>Windows Event Log Analysis</b>
- <b>Threat Detection</b>
- <b>Security Hardening</b>
- <b>Incident Investigation</b>
- <b>Identity and Access Management</b>
- <b>PowerShell</b>
- <b>Authentication Security</b>
- <b>Security Event Correlation</b>
