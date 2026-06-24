<p align="center">
  <img src="https://github.com/user-attachments/assets/02a7bd81-ee10-4cf1-aef9-c0649a03a4ea" width="200">
</p>

<h1 align="center">
Active Directory Security Lab
</h1>

<p align="center">
![Platform](https://img.shields.io/badge/Windows-Server%202022-blue)
![SIEM](https://img.shields.io/badge/SIEM-Splunk%20Enterprise-green)
![Hypervisor](https://img.shields.io/badge/VirtualBox-Lab-lightgrey)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
</p>

## Why This Project

Many Active Directory home labs focus primarily on administration tasks such as creating users, configuring Group Policy, or managing permissions.

This project takes a different approach.

The environment is designed to generate realistic Windows security telemetry that supports detection engineering, security monitoring, and incident investigation using Splunk Enterprise. Every configuration change, authentication event, and security control implemented within the lab serves as the foundation for additional security engineering projects documented throughout this GitHub portfolio.

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

## Environment

| Component | Technology |
|-----------|------------|
| Domain Controller | Windows Server |
| Endpoint | Windows 10 |
| SIEM | Splunk Enterprise |
| Attacker VM | Kali Linux |
| Hypervisor | VirtualBox |

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

## Future Enhancements
- Additional Group Policy security controls
- Windows Defender logging
- PowerShell logging
- Centralized dashboarding
- Threat hunting scenarios
- Detection engineering integrations

---

## Current Project Status

### Completed

- Active Directory deployment
- Organizational Unit design
- Role-Based Access Control (RBAC)
- Windows Security log forwarding
- Splunk Enterprise integration
- Sysmon deployment
- Account Lockout Policy implementation

### In Progress

- Authentication detection engineering
- Splunk dashboards
- Security event documentation

### Planned

- Process monitoring
- Threat hunting scenarios
- Detection tuning
- Security investigations

- ## Related Projects

- [Splunk Detection Engineering](https://github.com/CharlieWhiskeySec/splunk-detections)
- [SOC Investigations](https://github.com/CharlieWhiskeySec/soc-investigations)
- [Traffic Analysis](https://github.com/CharlieWhiskeySec/traffic-analysis)
