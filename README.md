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

## Overview

The **Active Directory Security Lab** serves as the identity foundation of **Charlie Whiskey Security Labs (CWSL)**, a fictional enterprise built to simulate a modern organization's security infrastructure and operations.

This repository documents the design, deployment, and ongoing development of the enterprise's Active Directory environment, including identity management, organizational structure, role-based access control, Group Policy, and Windows security administration.

The environment is designed to provide a realistic platform for hands-on security engineering, enabling other enterprise projects—including SIEM monitoring, detection engineering, incident response, and future hybrid identity initiatives—to operate within a centralized and consistently managed domain.


---

## Objectives

- Design an enterprise-style Active Directory environment.
- Implement Organizational Units (OUs) and security groups based on business functions.
- Configure Group Policy to enforce security settings.
- Simulate identity lifecycle operations including user provisioning, group management, authentication, and account lockouts.
- Forward Windows Security logs to Splunk Enterprise for monitoring and detection engineering.
- Document engineering decisions, troubleshooting, and lessons learned throughout the build process.

---

## Enterprise Role

Within Charlie Whiskey Security Labs, Active Directory provides:

- Centralized identity management
- Authentication and authorization
- Organizational Unit administration
- Group-based access control
- Security policy enforcement
- Windows endpoint management

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

---

## Current Features

- Active Directory domain services
- Organizational Unit structure
- Security group implementation
- Role-based access control (RBAC)
- Shared folder permissions
- Windows Security Event forwarding
- Sysmon telemetry collection
- Account Lockout Policy implementation
- Splunk integration

---

## Project Structure

---

## Current Status

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

