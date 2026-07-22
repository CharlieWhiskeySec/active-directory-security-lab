<p align="center">
  <img src="https://github.com/user-attachments/assets/02a7bd81-ee10-4cf1-aef9-c0649a03a4ea" width="200">
</p>
<br>

<h1 align="center">
Enterprise Active Directory Infrastructure
</h1>
> **Part of the Charlie Whiskey Security Labs Enterprise**

This repository documents the Active Directory infrastructure supporting **Charlie Whiskey Security Labs (CWSL)**. It serves as the identity foundation for the enterprise, providing centralized authentication, authorization, organizational structure, and security administration for all connected systems.

🏢 **Enterprise Hub:**  
https://github.com/CharlieWhiskeySec/charlie-whiskey-security-labs

## Overview

This project documents the design, implementation, and ongoing development of a Windows Active Directory environment built to simulate enterprise identity infrastructure and security operations. The lab serves as the foundation for security monitoring, detection engineering, and investigation projects using Splunk Enterprise.

Rather than focusing solely on Active Directory administration, this environment is designed to generate realistic Windows security telemetry that can be collected, analyzed, and investigated in a SIEM. As additional security controls and detections are implemented, this repository documents the underlying infrastructure that supports those projects.

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

