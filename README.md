<p align="center">
  <img src="https://github.com/user-attachments/assets/02a7bd81-ee10-4cf1-aef9-c0649a03a4ea" width="200">
</p>
<br>

<h1 align="center">
Enterprise Active Directory Infrastructure
</h1>
**Part of the Charlie Whiskey Security Labs Enterprise**

This repository documents the Active Directory infrastructure supporting **Charlie Whiskey Security Labs (CWSL)**. It serves as the identity foundation for the enterprise, providing centralized authentication, authorization, organizational structure, and security administration for all connected systems.

🏢 **Enterprise Hub:**  
https://github.com/CharlieWhiskeySec/charlie-whiskey-security-labs

## Overview

The **Active Directory Security Lab** serves as the identity foundation of **Charlie Whiskey Security Labs (CWSL)**, a fictional enterprise built to simulate a modern organization's security infrastructure and operations.

This repository documents the design, deployment, and ongoing development of the enterprise's Active Directory environment, including identity management, organizational structure, role-based access control, Group Policy, and Windows security administration.

The environment is designed to provide a realistic platform for hands-on security engineering, enabling other enterprise projects—including SIEM monitoring, detection engineering, incident response, and future hybrid identity initiatives—to operate within a centralized and consistently managed domain.

---

## Objectives

- Design and deploy a realistic enterprise Active Directory environment.
- Implement organizational units, users, groups, and role-based access control that reflect a modern business.
- Configure and manage Group Policy to enforce enterprise security standards.
- Generate realistic Windows authentication and security telemetry for SIEM monitoring and detection engineering.
- Support hands-on security investigations through controlled user activity and administrative operations.
- Establish a scalable identity platform for future enterprise services, including hybrid identity, endpoint management, and cloud security initiatives.

---

## Enterprise Role

Within Charlie Whiskey Security Labs (CWSL), Active Directory serves as the central identity platform for the enterprise. It provides the authentication, authorization, and administrative foundation that supports every connected system and security project.

Key responsibilities include:

Centralized authentication and authorization
Organizational Unit (OU) and account management
Role-Based Access Control (RBAC)
Group Policy administration and security enforcement
Windows endpoint identity management
Enterprise user, group, and computer lifecycle management
Security telemetry generation for SIEM monitoring and detection engineering

---

## Environment

| Component | Technology |
|-----------|------------|
| Domain Controller | Windows Server |
| Endpoint | Windows 10 |
| SIEM | Splunk Enterprise |
| Attacker VM | Kali Linux |
| Hypervisor | VirtualBox |

---

## Architecture

The Active Directory environment serves as the identity foundation of **Charlie Whiskey Security Labs (CWSL)**. Domain services provide centralized authentication, authorization, policy enforcement, and identity management while supporting enterprise security monitoring through Windows Event Logging and Sysmon telemetry.

```text
                    Charlie Whiskey Security Labs
                               │
        ┌──────────────────────┴──────────────────────┐
        │                                             │
   Windows Server 2022                         Ubuntu Server
  Active Directory & DNS                    Splunk Enterprise
        │                                             ▲
        │                                             │
        ▼                                             │
 Windows 11 Enterprise ─────── Sysmon & Event Logs ───┘
        │
        ▼
 User Authentication
 Group Policy
 RBAC
```

As the enterprise evolves, this architecture will expand to include hybrid identity, additional Windows systems, endpoint protection, security automation, and cloud security services.

---

## Current Capabilities

The Active Directory environment currently provides the following enterprise capabilities:

- Active Directory Domain Services (AD DS)
- DNS services for enterprise name resolution
- Organizational Unit (OU) hierarchy aligned with business departments
- Enterprise user, group, and computer account management
- Role-Based Access Control (RBAC) using security groups
- Group Policy Objects (GPOs) for centralized configuration and security enforcement
- Windows authentication and authorization
- Enterprise account lifecycle management
- Windows security event generation for Splunk enterprise
- Sysmon telemetry collection for security investigations

---

## Project Structure

```text
active-directory-security-lab/
├── docs/
│   ├── architecture/
│   ├── configuration/
│   ├── group-policy/
│   ├── organizational-units/
│   ├── security-groups/
│   └── users/
├── images/
├── scripts/
└── README.md
```

### Repository Contents

- **docs/** — Technical documentation covering the Active Directory environment, configuration, and security implementation.
- **images/** — Architecture diagrams, screenshots, and supporting visuals.
- **scripts/** — PowerShell scripts and automation used throughout the environment.
- **README.md** — Project overview, architecture, objectives, deployment details, and project status.
---

## Project Status

| Component | Status |
|-----------|:------:|
| Active Directory Domain Services | ✅ Operational |
| DNS Services | ✅ Operational |
| Organizational Unit Structure | ✅ Operational |
| Users & Groups | ✅ Operational |
| Role-Based Access Control (RBAC) | ✅ Operational |
| Group Policy | ✅ Operational |
| Windows Security Event Logging | ✅ Operational |
| Sysmon Telemetry | ✅ Operational |
| Splunk Enterprise Integration | ✅ Operational |
| Enterprise Documentation | 🚧 In Progress |
| Hybrid Identity (Microsoft Entra ID) | 📅 Planned |
| Enterprise PKI | 📅 Planned |
| Windows Defender Integration | 📅 Planned |

---

## Enterprise Expansion

- Hybrid Identity (Entra ID)
- Additional Windows Workstations
- Additional Servers
- Tiered Administration
- Windows Event Forwarding
- Enterprise PKI

## Related Enterprise Projects

- Charlie Whiskey Security Labs
- Splunk Detection Engineering
- SOC Investigations
- Traffic Analysis

