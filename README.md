<p align="center">
  <img src="https://github.com/user-attachments/assets/02a7bd81-ee10-4cf1-aef9-c0649a03a4ea" width="200">
</p>

<p align="center">
  <img src="images/banner.png" alt="Active Directory Security Lab Banner">
</p>

<h1 align="center">Active Directory Security Lab</h1>

<p align="center">
  <strong>Part of the Charlie Whiskey Security Labs Enterprise</strong><br>
  Enterprise Identity • Authentication • Authorization • Group Policy • RBAC
</p>

<p align="center">
  🏢 <a href="https://github.com/CharlieWhiskeySec/charlie-whiskey-security-labs"><strong>Enterprise Hub</strong></a>
</p>

---

# Overview

The **Active Directory Security Lab** serves as the enterprise identity platform for **Charlie Whiskey Security Labs (CWSL)**.

This environment provides centralized authentication, authorization, Group Policy administration, and Role-Based Access Control (RBAC) while generating Windows security telemetry consumed by Splunk Enterprise for detection engineering and security investigations.

---

# Objectives

- Design and deploy a realistic enterprise Active Directory environment.
- Implement organizational units, users, groups, and role-based access control.
- Centralize authentication and authorization.
- Enforce enterprise security policies through Group Policy.
- Generate Windows Security and Sysmon telemetry for SIEM monitoring.
- Provide the identity foundation for enterprise security engineering projects.

---

# Enterprise Role

Within Charlie Whiskey Security Labs, Active Directory provides:

- Enterprise authentication
- Identity lifecycle management
- Organizational Unit administration
- Role-Based Access Control (RBAC)
- Group Policy administration
- Windows endpoint management
- Enterprise security telemetry

---

# Environment

| Component | Details |
|-----------|---------|
| Enterprise | Charlie Whiskey Security Labs |
| Platform | Oracle VirtualBox |
| Domain Controller | Windows Server 2022 |
| Client | Windows 11 Enterprise |
| SIEM | Splunk Enterprise |
| Monitoring | Sysmon, Windows Event Logs |
| Supporting Systems | Ubuntu Server, Kali Linux |

---

# Enterprise Architecture

```text
                    Charlie Whiskey Security Labs
                               │
                 ┌─────────────┴─────────────┐
                 │                           │
        Identity Services            Security Operations
                 │                           │
        Windows Server 2022          Splunk Enterprise
        Active Directory & DNS              ▲
                 │                          │
                 │                          │
      ┌──────────┴──────────┐               │
      │                     │               │
Windows 11 Enterprise   Future Systems      │
      │                                     │
      └──── Sysmon & Windows Event Logs ────┘
```

---

# Current Capabilities

- Active Directory Domain Services (AD DS)
- DNS services
- Organizational Unit hierarchy
- Enterprise user, group, and computer management
- Role-Based Access Control (RBAC)
- Group Policy administration
- Windows authentication and authorization
- Enterprise account lifecycle management
- Windows Security Event generation
- Sysmon telemetry collection
- Splunk Enterprise integration

---

# Project Structure

```text
active-directory-security-lab/
├── docs/
├── images/
├── scripts/
└── README.md
```

| Folder | Purpose |
|---------|---------|
| docs | Technical documentation |
| images | Screenshots, diagrams, and graphics |
| scripts | PowerShell automation |
| README.md | Project overview |

---

# Project Status

| Component | Status |
|-----------|:------:|
| Active Directory Domain Services | ✅ Operational |
| DNS | ✅ Operational |
| Organizational Unit Structure | ✅ Operational |
| Users & Groups | ✅ Operational |
| RBAC | ✅ Operational |
| Group Policy | ✅ Operational |
| Windows Event Logging | ✅ Operational |
| Sysmon Telemetry | ✅ Operational |
| Splunk Integration | ✅ Operational |
| Enterprise Documentation | 🚧 In Progress |
| Hybrid Identity | 📅 Planned |
| Enterprise PKI | 📅 Planned |
| Microsoft Defender | 📅 Planned |

---

# Future Enhancements

- Microsoft Entra ID
- Hybrid Identity
- Windows Event Forwarding
- Enterprise PKI
- Microsoft Defender
- Security Automation
- Additional Enterprise Workstations
- Tiered Administration

---

# Related Enterprise Projects

| Repository | Description |
|------------|-------------|
| 🏢 Charlie Whiskey Security Labs | Enterprise documentation and architecture |
| 📊 Splunk Detections | Detection engineering and SIEM |
| 🔍 SOC Investigations | Security investigations and incident response |
| 🌐 Traffic Analysis | Network monitoring and packet analysis |

---

<p align="center">

Built as part of the **Charlie Whiskey Security Labs** enterprise.

</p>

