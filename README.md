# OPNsense-Firewall

# 🛡️ Enterprise Firewall & IDS/IPS Lab using OPNsense & Suricata

A hands-on enterprise-style network security lab built using **OPNsense Firewall**, **Suricata IDS/IPS**, and **VMware Workstation**. The objective of this project is to simulate real-world attack scenarios, inspect network traffic, detect malicious activities, and automatically block suspicious traffic using Intrusion Prevention System (IPS).

---

# 📌 Project Objectives

- Build an enterprise firewall lab
- Configure Stateful Firewall Rules
- Deploy Suricata IDS/IPS
- Simulate attacks from Kali Linux
- Detect and block malicious traffic
- Analyze alerts and firewall logs

---

# 🏗️ Lab Architecture

```
                   Internet
                      │
                 WAN (NAT)
                      │
        +---------------------------+
        |        OPNsense           |
        | Firewall + Suricata IPS   |
        +---------------------------+
                │ LAN (192.168.50.0/24)
        ┌───────────────┴───────────────┐
        │                               │
   Kali Linux                      Windows 10
   (Attacker)                      (Victim)
```

---

# 🛠️ Technologies Used

- VMware Workstation
- OPNsense Firewall
- Suricata IDS/IPS
- Emerging Threats (ET Open) Rules
- Kali Linux
- Windows 10

---

# 🔧 Security Tools

- Nmap
- Nikto
- Gobuster *(Enumeration only)*

---

# ⚙️ Firewall Features

- Stateful Firewall
- LAN Security Rules
- ICMP Filtering
- HTTP/HTTPS Inspection
- Intrusion Detection
- Intrusion Prevention
- Real-Time Alerts
- Firewall Live Logs

---

# 🧪 Attack Simulation

| Attack Tool | Purpose | Result |
|-------------|---------|--------|
| Nmap | Port Scanning | ✅ Detected & Blocked |
| Nikto | Web Server Scan | ✅ Detected & Blocked |
| Gobuster | Directory Enumeration | ✅ Executed (Detection rules will be expanded in future) |

---

# 🔄 Workflow

```
Kali Linux
      │
      ▼
Attack Generated
      │
      ▼
OPNsense Firewall
      │
      ▼
Suricata Inspection
      │
      ▼
Rule Matching
      │
      ▼
Alert Generated
      │
      ▼
IPS Block Action
```

---

# 📸 Project Screenshots

- VMware Topology
- OPNsense Dashboard
- Firewall Rules
- Suricata Configuration
- IPS Mode
- Nmap Scan
- Nmap Alert
- Nikto Scan
- Nikto Alert
- Firewall Live Logs

---

# 🎯 Learning Outcomes

- Firewall Rule Management
- Network Segmentation
- IDS vs IPS
- Suricata Rule Management
- Attack Detection
- Threat Monitoring
- Security Event Analysis

---

# 🚀 Future Improvements

- Add custom Suricata rules
- Improve Gobuster detection
- Integrate Splunk SIEM
- Integrate Wazuh
- Add Sigma-based detections
- Deploy OWASP Juice Shop for web attack simulations

---

# 📄 Conclusion

This project demonstrates the deployment of an enterprise-style Firewall and IDS/IPS solution capable of monitoring network traffic, detecting malicious activities, generating alerts, and blocking attacks in real time using open-source security technologies.

---

⭐ If you found this project useful, feel free to star the repository.
