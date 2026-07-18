# 🛡️ Enterprise Threat Detection & Monitoring Lab

> An end-to-end Security Operations Center (SOC) home lab demonstrating enterprise threat detection, attack simulation, log analysis, and incident investigation using **Wazuh SIEM, Snort IDS, Sysmon, Kali Linux, and Windows 11**.

<p align="center">

![Wazuh](https://img.shields.io/badge/Wazuh-v4.14-blue)
![Sysmon](https://img.shields.io/badge/Sysmon-Microsoft-success)
![Snort](https://img.shields.io/badge/Snort-IDS-red)
![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-E95420)
![Windows](https://img.shields.io/badge/Windows-11-0078D6)
![Kali](https://img.shields.io/badge/Kali-Linux-557C94)

</p>

<p align="center">
  <img src="Lab Architecture/Enterprise-Threat-Detection-Monitoring-Lab.png" width="100%">
</p>

---

# 📖 Project Overview

This project demonstrates the design and implementation of a complete **Enterprise Threat Detection & Monitoring Laboratory** built in a virtualized environment.

The objective of this project was to simulate real-world cyber attacks against a Windows endpoint while collecting, monitoring, and investigating security events using an enterprise-grade SIEM.

The lab follows the complete Security Operations Center (SOC) workflow:

- Attack Simulation
- Event Collection
- Threat Detection
- Log Correlation
- Security Monitoring
- Incident Investigation
- Reporting & Documentation

---

# 🎯 Project Objectives

- Build an enterprise SOC home lab
- Deploy Wazuh SIEM
- Integrate Windows endpoint logging
- Configure Sysmon for detailed endpoint telemetry
- Configure Snort IDS for network intrusion detection
- Simulate real-world attacks
- Detect attacks inside Wazuh Dashboard
- Document findings professionally

---

# 🏗️ Lab Architecture

The lab consists of three primary machines.

| Machine | Role |
|----------|------|
| Kali Linux | Attacker Machine |
| Windows 11 | Monitored Endpoint |
| Ubuntu Server | Wazuh SIEM Server |

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Kali Linux | Attack Simulation |
| Windows 11 | Target Endpoint |
| Ubuntu Server | Wazuh Server |
| Wazuh SIEM | Security Monitoring |
| Sysmon | Endpoint Telemetry |
| Snort IDS | Network Intrusion Detection |
| VirtualBox | Virtualization |
| Windows Event Logs | Security Logging |

---

# ⚔️ Attack Scenarios

The following attacks were successfully simulated and detected.

| Attack | Detection Source | Status |
|---------|-----------------|--------|
| ICMP Reconnaissance | Snort → Wazuh | ✅ |
| TCP SYN / Nmap Scan | Snort → Wazuh | ✅ |
| SSH Brute Force (Hydra) | Snort → Wazuh | ✅ |

---

# 🔍 Detection Workflow

```
Kali Linux
      │
      ▼
Attack Traffic
(ICMP / TCP / SSH)
      │
      ▼
Windows 11 Endpoint
      │
      ├── Sysmon Logs
      ├── Windows Event Logs
      └── Snort Alerts
             │
             ▼
Ubuntu Server
(Wazuh SIEM)
             │
             ▼
Threat Detection
             │
             ▼
SOC Investigation
```

---

# 📊 MITRE ATT&CK Mapping

| Attack | MITRE Technique |
|---------|-----------------|
| ICMP Reconnaissance | T1595 - Active Scanning |
| Nmap Scan | T1046 - Network Service Discovery |
| SSH Brute Force | T1110 - Brute Force |

---

# 📸 Proof of Concept

The repository contains screenshots demonstrating each stage of the project.

All screenshots are available in the **[Proof Of Concept](Proof-Of-Concept/)** folder.

---

# 💡 Skills Demonstrated

- Security Operations Center (SOC)
- Security Information & Event Management (SIEM)
- Threat Detection
- Threat Hunting
- Incident Investigation
- Endpoint Monitoring
- Windows Event Analysis
- Network Intrusion Detection
- Log Correlation
- Linux Administration
- Windows Administration
- Network Security
- MITRE ATT&CK Framework

---

# 📄 Documentation

The complete technical documentation is available in the **[Documentation](Documentation/)** folder.

📄 **Project Report**

- [Enterprise Threat Detection & Monitoring Lab.pdf](Documentation/ENTERPRISE%20THREAT%20DETECTION.pdf)

---

# 👨‍💻 Author

**Rahul Reghu Rajan**

- 🎓 BCA Graduate
- 🛡️ Advanced Diploma in Cyber Defence (ADCD)
- 🎯 EC-Council Certified Ethical Hacker (CEH v13)

### Connect with Me

🌐 **Portfolio**  
https://rahulhub.vercel.app

💼 **LinkedIn**  
https://www.linkedin.com/in/rahul-reghu-rajan/

---

<p align="center">

**Enterprise Threat Detection & Monitoring Lab**

Designed, Implemented & Documented by **Rahul Reghu Rajan**

</p>

---



