# 🏠💼 Home Enterprise Lab Environment

> ⚙️ A personal enterprise-grade lab designed to replicate a real-world IT environment for hands-on learning, security testing, and automation. While cybersecurity is a primary focus, this long-term project also supports deep exploration of systems administration, networking, scripting, and infrastructure management. The lab serves as a platform for end-to-end experimentation across blue team operations and broader IT workflows.

This project represents a personal initiative to build a live enterprise-grade lab environment using both physical and virtual systems. The goal is to simulate blue team operations, implement core IT infrastructure, automate workflows, and experiment with adversary emulation in a safe, controlled setting.

---

## 🧱 Planned Architecture

- 🖥️ **4 Physical Workstations**
  - Each running local virtual machines via **VMware Workstation Player**
- 📡 **DHCP Server**
- 🧭 **DNS Server**
- 🏢 **Active Directory Domain Controller**
  - Full domain setup with organizational units, user roles, and GPOs
- 🔗 **All systems domain-joined**
- 🔐 **Firewall and segmented internal network (planned)**

---

## 🎯 Project Objectives

- Deploy and configure a fully functioning Windows enterprise environment
- Automate system setup, user provisioning, and GPO enforcement with PowerShell
- Simulate real-world cyberattacks and conduct detection, triage, and remediation
- Perform vulnerability scans, patch management, and system hardening
- Connect endpoints to Microsoft Defender for Endpoint and forward telemetry to Sentinel
- Run threat hunting queries and analyze behavior using KQL
- Build documentation and playbooks for blue team workflows

---

## 🧰 Tools & Technologies (Planned/Active)

- **VMware Workstation Player** – Local virtualization
- **Windows Server & Windows 10/11 VMs** – Infrastructure components
- **Active Directory, DNS, DHCP** – Core network services
- **Microsoft Defender for Endpoint** – Endpoint detection and response (EDR)
- **Microsoft Sentinel** – SIEM platform for log ingestion and analysis
- **PowerShell** – Scripting and automation
- **KQL (Kusto Query Language)** – Threat hunting in Sentinel
- **Nessus or OpenVAS** – Vulnerability scanning
- **MITRE ATT&CK** – Adversary simulation reference

---

## 🚧 Development Timeline

This lab is being developed in phases due to hardware costs and system complexity. Progress will be tracked here as each module is built and tested.

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 1 | Acquire and set up 4 physical machines | ⏳ Planning |
| Phase 2 | Build AD, DNS, DHCP server and join workstations | 🔜 Upcoming |
| Phase 3 | Deploy Defender for Endpoint & connect to Sentinel | 🔜 Upcoming |
| Phase 4 | Automate provisioning and GPO deployment | 🔜 Upcoming |
| Phase 5 | Simulate attacks, detect and remediate | 🔜 Upcoming |

---

> 🛡️ This environment will serve as the foundation for future threat hunting labs, detection engineering exercises, security automation projects, and vulnerability remediation practice.

📌 *This project is evolving over time as my resources and skills grow. Each phase will be fully documented as it is completed.*
