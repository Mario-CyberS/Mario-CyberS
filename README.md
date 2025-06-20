# Hello, I'm Mario Tagaras
<a href="https://www.linkedin.com/in/mario-gt" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

I am a driven Cyber Security enthusiast with hands-on experience in SIEM deployment/configuration, scripting, back-up automation, threat log analysis, network/endpoint hardening. I spent a year as a Cyber Security Analyst Intern at Diverse Computing, Inc., where I deployed and tuned Wazuh (open-source) SIEMs, on RHEL/Almalinux servers for centralized log aggregation, as well as threat detection/alerting. I also deployed numerous Wazuh agents across plenty of endpoints/devices for close agent-based monitoring like FIM log collection. I've automated ASA firewall backups using Python/Bash scripts I wrote and hardened, along side working with tools like Zabbix for monitoring and automation disruption alerting.

I also continuously run a homelab where I build secure networking environments using Raspberry Pi as a firewall/NAT setup, Tailscale as a VPN for private device network, and Mullvad as a traffic exit node. One of my key projects is the Automated Cyberscan Orchestrator, a collaborative design with a co-developer to automate bug bounty reconnaissance. It uses Python/Selenium/undetected-chromedriver to scrape for bounty targets from targeted bounty program sites, routes findings through an LLM for context-aware tool selection, and safely automates the execution of recon tools based on the given data and thought analysis, ending with a well organized automated report generation ready for review, with plans to implement a CMP server for proper orchestration, this would lay the groundwork for scalable, automated vulnerability workflows.

I am CompTIA Security+ SY0-701 certified and currently studying for my CySa+ certification. I am actively hunting for an entry-level role as an SOC Analyst or Cyber Security Analyst. I am passionate about Cyber Security monitoring/detection/response automated and manual work flows, and international regulation compliance. This would include CISA’s SIEM/SOAR guidelines for proper implementation and use, alongside compliance with government regulations like NIST 800-171, HIPPA, PCI DSS, FERPA, GDPR, etc. 

## 🏫 Education  
**Florida State University (FSU)**  
- Bachelor’s Degree – Computer Science, Cyber Criminology (Graduation: May 2025)

## 💼 Experience
**Cybersecurity Analyst Intern** – Diverse Computing, Inc.  
  *(May 2024 – April 2025)*  
  - Hands-on experience with installing/deploying single node Wazuh SIEM servers
  - Gained hands-on experience with security event monitoring, endpoint management, and log analysis.
  - Partnered in SIEM configurations, vulnerability assessments, and incident investigations.
  - Developed scripts to automate common SOC tasks and improve operational efficiency.
  - Deep exposure to CJIS compliance standards and government cybersecurity practices.
 
 **Cybersecurity Homelab Projects**  
  - Collaborative project (Automated Cyberscan Orchestrator) that scrapes bug bountie programs and automates the cyber flows for vulnerability discovery.
  - Deployed Wazuh SIEM for endpoint and network security monitoring.
  - Configured rsyslog, syslog ingestion, and log rotation for firewall logs.
  - Designed backup automation using Bash, Expect, and Rancid tools for Cisco ASA configurations.
  - TailScale Virtual Private Network Set-up, Wake-on-LAN, RDP, Pi as Firewall/NAT, etc.
  - My projects are listed below ⬇︎

## 📜 Certificates 
- CompTIA Security+ SY0-701
- Sec+ Certification Date: June 19, 2025

![CompTIA-Security-Plus-Logo-small](https://github.com/user-attachments/assets/019e7bfe-11cb-491d-9c5e-22cf334eaee3)

## 🎯 Objective
I'm a cybersecurity-focused professional with hands-on experience in SIEM deployment, security automation, and incident detection/response. I'm actively seeking a entry-level Cybersecurity role where I can apply my skills in proactive/automated monitoring, scripting, and system hardening to support detection and response efforts. My goal is to contribute to a fast-paced security team while continuing to build on my understanding of SIEM and SOAR best practices.

## 🚀 Projects  

### 🔷 Wazuh SIEM Project:

#### [Deploying Wazuh SIEM](https://github.com/Mario-CyberS/Deploying-Wazuh-SIEM/blob/main/README.md)  
**Description:** This project demonstrates the step-by-step process of setting up a **Wazuh SIEM Manager** on a **RHEL VM** using **VMware Workstation 17**. It includes installing RHEL 9.5 minimal iso, installing VMware workstation, deploying RHEL VM, installing Wazuh, and accessing the Wazuh Web UI for real-time security monitoring.

#### [Syslog Wazuh Configuration](https://github.com/Mario-CyberS/Syslog-Wazuh-Configuration/blob/main/README.md)
**Description:** This project details how to configure Wazuh SIEM and rsyslog on a RHEL-based system to ingest syslog data from a Cisco ASA firewall. It covers editing the Wazuh ossec.conf, creating a dedicated log file, adjusting rsyslog rules, and verifying log ingestion for real-time network traffic monitoring.

#### [Logrotate Wazuh ASA.log](https://github.com/Mario-CyberS/Logrotate-Wazuh-ASA.log/blob/main/README.md)
**Description:** This project outlines how to configure a custom logrotate policy on a RHEL-based Wazuh server to automatically rotate, compress, and manage the siteasa.log file that stores Cisco ASA firewall logs. It includes crontab scheduling for daily rotation and service restart handling to ensure uninterrupted log ingestion.

#### [Indexer Tuning and ISM Wazuh](https://github.com/Mario-CyberS/Indexer-Tuning-and-ISM-Wazuh/blob/main/README.md)
**Description:** This project focuses on optimizing the Wazuh Indexer for a single-node setup by tuning shard counts, replica settings, index lifecycle policies (ISM), and increasing heap memory usage to avoid cluster overload and log ingestion issues.

#### [Wazuh Agent Deployment](https://github.com/Mario-CyberS/Wazuh-Agent-Deployment/blob/main/README.md)
**Description:** This project provides step-by-step instructions for deploying and configuring Wazuh agents on endpoint machines and managing agent connections to the Wazuh Manager. It also covers agent removal using the CLI.

#### [Rancid Installation and Script Automation](https://github.com/Mario-CyberS/Rancid-Installation-and-Script-Automation/blob/main/README.md)
**Description:** This project explains how to create a Rancid user on the Wazuh server, set up automated daily backups of Cisco ASA running configurations using Rancid Tool, Expect scripting, Bash scripting, and crontab scheduling.

#### [Zabbix Agent on Wazuh Server for Monitoring](https://github.com/Mario-CyberS/Zabbix-Agent-on-Wazuh-Server-for-Monitoring/blob/main/README.md)
**Description:** This project documents how to install and configure the Zabbix Agent on the Wazuh SIEM server to enable detailed monitoring using the Zabbix frontend. It includes service health checks, /var disk usage alerts, Rancid backup verification, and SELinux policy adjustments for secure command execution.

#### [File Integrity Monitoring (FIM) & Who-Data Setup in Wazuh](https://github.com/Mario-CyberS/FIM-Who-Data-on-Agents-and-Server/blob/main/README.md)
**Description:** This project documents how to configure FIM and enable Who-Data auditing on Wazuh agents or the manager itself, enabling visibility into who made changes to monitored files, from what process, and when.

#### [ClamAV Wazuh Integration](https://github.com/Mario-CyberS/ClamAV-Wazuh-Integration/blob/main/README.md)
**Description:** This project outlines how to integrate ClamAV antivirus with the Wazuh SIEM for real-time malware detection by forwarding ClamAV logs into Wazuh for alerting, monitoring, and dashboard visualization.

#### [Wazuh Slack Integration](https://github.com/Mario-CyberS/Wazuh-Slack-Integration/blob/main/README.md)
**Description:** This project documents the integration of Wazuh with Slack via Incoming Webhooks, enabling real-time alert notifications from the Wazuh Manager to a private Slack channel.

#### [Wazuh Postfix Email Integration](https://github.com/Mario-CyberS/Wazuh-Postfix-Email-Integration/blob/main/README.md)
**Description:** This project documents the integration of Wazuh with Postfix and a custom Python script to send real-time security alerts via Gmail SMTP, allowing structured, secure, and reliable email notifications directly from your SIEM server.

### 🔶 TailScale Private Network Set-up:

#### [Tailscale RDP Setup From Mac To Windows](https://github.com/Mario-CyberS/Tailscale-RDP-Setup-From-Mac-to-Windows/blob/main/README.md)
**Description:** This project documents the configuration and secure setup of **Remote Desktop Protocol (RDP)** access from a **MacBook** to a **Windows PC** using **Tailscale**, enabling private, encrypted access with no need for port-forwarding or static IPs.

#### [RaspbPi as mini Firewall/NAT/WoL Gateway for PC](https://github.com/Mario-CyberS/RaspbPi-as-mini-Firewall-NAT-Gateway/blob/main/README.md)
**Description:** This project demonstrates how to use a Raspberry Pi as a firewall and NAT gateway, allowing a MacBook to remotely wake and access a Windows PC via Tailscale, while routing all PC internet traffic through the Pi. The setup is designed to work even on captive portal Wi-Fi networks via a travel router.

#### [Mullvad as Tailscale Exit Node](https://github.com/Mario-CyberS/Mullvad-as-Tailscale-Exit-Node/blob/main/README.md)
**Description:** This project documents how to configure a Raspberry Pi to act as a secure internet gateway for a connected PC using Mullvad VPN (via WireGuard) while still allowing remote access over Tailscale. It ensures all PC traffic is routed through Mullvad, while preserving RDP and SSH access from a MacBook using Tailscale.

### ♦️ Automated Orchestration of Cyberscan Tools:

#### [Automated Cyberscan Orchestrator](https://github.com/Mario-CyberS/Automated-Cyberscan-Orchestrator/edit/main/README.md)
**Description:** This project builds an automated framework for discovering and testing bug bounty targets by orchestrating scraping, AI-driven tool recommendations, recon scanning, and report generation. It leverages Python modules to extract bounty data, route it through an LLM for optimal tool selection, and safely run reconnaissance tools; laying the foundation for fully automated vulnerability reporting workflows. Future enhancements include the integration of a CMP (Command Management Platform) server to coordinate task dispatching, tool execution, and job tracking across distributed agents.

## 📚 Skills

| Skill                                         | Associations         |
|-----------------------------------------------|----------------------------|
| Operating Systems (CLI Proficiency) | Mac - Windows - Linux - AlmaLinux - RHEL - CentOS - Debian - Ubuntu - Kali - Raspberry Pi|
| Programming & Scripting | Bash - Expect - C++ - C - Python - Java - JavaScript - Markdown|
| Monitoring & Security Tools | Zabbix - SNMP - Cradlepoints - Wazuh - Rancid - Suricata - ClamAV - Splunk - rsyslog - WireShark - Netstat|
| Hypervisors/Virtualization & VMs Deployment/Configuration| Linode - Parallels - VMware Fusion Pro - VMware Workstation Pro - VirtualBox - Azure|
| Security Operations & SIEM Management | Installing & Deploying Wazuh SIEM Manager & Agents - Integrating 3rd party apps into Wazuh|
| SIEM Configuration & Training | Training SysOps, Support, and Network Teams on Wazuh SIEM - ISM Policy configuration - Wazuh OpenSearch Index tuning - RBAC - Syslog ingestion|
| Security Log Analysis & Incident Response | Monitoring Wazuh logs, navigating the web interface, configuring Slack/email for Alerts|
| Automation & Scripting for Security Tasks | Writing & Automating Bash/Expect Scripts for Log Rotation & ASA Config Backups using Rancid|
| Networking Tools | TailScale VPN, Cisco, Suricata IPS/IDS, MullVad Exit Node, Nmap, Rancid, Firewall Rules List |
| Text Editors | VI, Nano, Windows Note Pad|

## 🛠️ Tools

### Network
<div>   
    <a href="https://www.wireshark.org/" target="_blank"><img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <a href="https://suricata.io/download/" target="_blank"><img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" />
    <a href="https://nmap.org/download.html" target="_blank"><img src="https://img.shields.io/badge/-Nmap-00457C?&style=for-the-badge&logo=nmap&logoColor=white" />
    <a href="https://shrubbery.net/rancid/" target="_blank"><img src="https://img.shields.io/badge/-Rancid-800000?&style=for-the-badge&logoColor=white" />
    <a href="https://tailscale.com/" target="_blank"><img src="https://img.shields.io/badge/-Tailscale-005AE0?&style=for-the-badge&logo=Tailscale&logoColor=white" />
    <a href="https://mullvad.net/en/vpn" target="_blank"><img src="https://img.shields.io/badge/-Mullvad%20Exit%20Node-FFCC00?&style=for-the-badge&logo=Mullvad&logoColor=000000" />
    <a href="https://linux.die.net/man/8/iptables" target="_blank"><img src="https://img.shields.io/badge/-iptables-4B8BBE?style=for-the-badge&logo=linux&logoColor=white" />

</div>

### SIEM/Monitoring
<div>
    <a href="https://documentation.wazuh.com/current/quickstart.html" target="_blank"><img src="https://img.shields.io/badge/-Wazuh-0078D4?&style=for-the-badge&logo=Wazuh&logoColor=white" />
    <a href="https://www.splunk.com/en_us/download.html" target="_blank"><img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <a href="https://www.zabbix.com/download" target="_blank"><img src="https://img.shields.io/badge/-Zabbix-DC143C?&style=for-the-badge&logo=Zabbix&logoColor=white" />
</div>


### Endpoint
<div>   
    <a href="https://documentation.wazuh.com/current/installation-guide/wazuh-agent/index.html" target="_blank"><img src="https://img.shields.io/badge/-Wazuh_Agent-0078D4?&style=for-the-badge&logo=Wazuh&logoColor=white" />
    <a href="https://www.splunk.com/en_us/download/universal-forwarder.html" target="_blank"><img src="https://img.shields.io/badge/-Splunk_Forwader-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <a href="https://www.zabbix.com/download_agents" target="_blank"><img src="https://img.shields.io/badge/-Zabbix_Agent-DC143C?&style=for-the-badge&logo=Zabbix&logoColor=white" />
</div>


### CLOUD
<div>
    <a href="https://azure.microsoft.com/en-us/products/microsoft-sentinel" target="_blank"><img src="https://img.shields.io/badge/-Azure_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft-Azure&logoColor=white" />
</div>

---

<!--- ## Download [My Resume (PDF)](https://github.com/Mario-CyberS/Mario-CyberS/raw/main/Mario_Tagaras_Resume.pdf) --->


