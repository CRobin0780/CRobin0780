# 👋 Hi, I'm Chris Robinson

🎯 Military veteran transitioning into IT/Cybersecurity | SysAdmin & SOC Analyst  
🛡️ Building a production-grade enterprise SOC homelab: **Fort Reign**  
📍 Colorado Springs, CO | Active Secret Clearance | Open to SysAdmin & Azure Admin roles  
💼 Client Support Administrator @ Apex Systems → Amentum IRES (DoD)

---

## 🏰 Fort Reign — Enterprise SOC Homelab

Fort Reign is a fully operational enterprise-style infrastructure and security operations environment built on a 3-node Proxmox cluster. It mirrors real-world DoD and enterprise environments with hybrid identity, centralized SIEM, endpoint detection, threat intelligence, and automated infrastructure management.

### Infrastructure

| Component | Details |
|---|---|
| **Hypervisors** | 3-node Proxmox cluster — Dell T7810 (64GB), OptiPlex 7070 (32GB), OptiPlex 3050 (16GB) |
| **Network** | Ubiquiti ER-X router · Cisco SG300 managed switch · 4-VLAN design (Management, Enterprise, Attack, IoT) |
| **Domain** | Windows Server 2022 Active Directory · DNS · DHCP · Group Policy |
| **Hybrid Identity** | Microsoft Entra Connect · Password Hash Sync · MFA · DCSync attack path mapped via BloodHound |
| **Automation** | Ansible control node managing 6 Linux servers · Self-hosted Gitea version control |

---

## 🔐 Security Stack (Phases 1–5)

### SIEM & Monitoring
| Tool | Status | Details |
|---|---|---|
| **Wazuh** | ✅ Live | 3 agents · Sysmon integrated · DC01, FRG-W10-01, FRG-W10-02 |
| **Splunk** | ✅ Live | Wazuh forwarding pipeline · Detection dashboards in progress |
| **Security Onion** | ✅ Live | SPAN port monitoring · IDS · PCAP analysis |

### SOC Tools
| Tool | Status | Details |
|---|---|---|
| **Velociraptor** | ✅ Live | Endpoint forensics & live response · 3 agents enrolled · VQL hunts running |
| **MISP** | ✅ Live | Threat intelligence platform · 5 active feeds (CIRCL, Feodo, URLhaus, MalwareBazaar, Phishtank) |
| **BloodHound CE** | ✅ Live | AD attack path analysis · DCSync rights mapped · MSOL sync account finding documented |

---

## 📁 Repositories

### 🧱 [fortreign-sysadmin-lab](https://github.com/CRobin0780/fortreign-sysadmin-lab)
Enterprise infrastructure build — Active Directory, DNS, DHCP, Group Policy, VLAN segmentation, Proxmox cluster, Ansible automation, static IP management.

**Key skills demonstrated:**
- Windows Server 2022 AD deployment and hardening
- 4-VLAN network architecture with inter-VLAN routing
- Ansible playbooks for patch management and configuration
- Entra Connect hybrid identity with Password Hash Sync
- Self-hosted Git (Gitea) for infrastructure version control

### 🔐 [fortreign-soc-lab](https://github.com/CRobin0780/fortreign-soc-lab)
Full SOC stack deployment — SIEM pipeline, endpoint detection, threat intelligence, and incident response.

**Key skills demonstrated:**
- Wazuh SIEM with Sysmon telemetry and Windows audit policies
- Splunk log aggregation with Wazuh Universal Forwarder
- Security Onion network security monitoring with SPAN port
- Velociraptor endpoint forensics — VQL hunts across all endpoints
- MISP threat intelligence with automated IOC feed ingestion
- BloodHound AD attack path analysis — DCSync exposure documented
- IR report writing (IR-2026-001: DCSync rights via Entra Connect)

### ☁️ [fortreign-az104-lab](https://github.com/CRobin0780/fortreign-az104-lab)
Azure hybrid identity and cloud administration lab — extends on-prem Fort Reign into Azure.

**Key skills demonstrated:**
- Microsoft Entra ID tenant configuration
- Entra Connect hybrid identity synchronization
- MFA deployment and Conditional Access policy design
- RBAC and Azure resource management

---

## 🛠️ Technical Skills

**Infrastructure & Systems**
`Proxmox` `Windows Server 2022` `Active Directory` `DNS` `DHCP` `Group Policy` `Linux (Ubuntu 24.04)` `Rocky Linux`

**Security Operations**
`Wazuh` `Splunk` `Security Onion` `Velociraptor` `MISP` `BloodHound` `Sysmon` `IDS/IPS` `PCAP Analysis` `Threat Hunting` `Incident Response`

**Identity & Cloud**
`Microsoft Entra ID` `Entra Connect` `Hybrid Identity` `MFA` `Azure` `RBAC` `Conditional Access`

**Networking**
`VLANs` `Inter-VLAN routing` `Ubiquiti EdgeOS` `Cisco SG300` `pfSense` `Wireshark` `nmap`

**Automation & DevOps**
`Ansible` `Bash` `PowerShell` `Python` `Gitea` `Git` `systemd` `Netplan`

**Frameworks & Compliance**
`NIST RMF` `MITRE ATT&CK` `NIST 800-53` `DoD 8570` `ITIL v4`

---

## 📜 Certifications

| Certification | Status |
|---|---|
| CompTIA A+ | ✅ Earned |
| CompTIA Network+ | ✅ Earned |
| CompTIA Security+ CE | ✅ Earned |
| AZ-900 Azure Fundamentals | ✅ Earned |
| ITIL v4 Foundation | ✅ Earned |
| AZ-104 Azure Administrator | 🔄 In Progress |
| CompTIA Linux+ | 📅 Planned |
| RHCSA | 📅 Planned |
| CCNA | 📅 Planned |

---

## 🎖️ Military Background

4 years U.S. Military service as a Logistics Officer — supply chain management, 
resource allocation, mission planning, and leading teams under operational conditions. 
The same discipline applied to building Fort Reign: structured phases, documented SOPs, 
version-controlled configs, and operational logging.

Active Secret clearance.



---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Christopher%20Robinson-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/christionirobinson/)
[![GitHub](https://img.shields.io/badge/GitHub-CRobin0780-181717?style=flat&logo=github)](https://github.com/CRobin0780)

---

*Fort Reign is an ongoing build. New tools, attack simulations, and documentation added regularly.*
