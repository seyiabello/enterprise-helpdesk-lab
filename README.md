# Enterprise Helpdesk Lab (Active Directory & Windows Server)

## Overview
This project demonstrates hands-on experience with enterprise IT support tasks using a Windows Server 2022 Active Directory environment and Windows 10 clients. The lab simulates real-world helpdesk scenarios including user management, access control, Group Policy, and troubleshooting.

## Technologies Used
- Windows Server 2022 (Domain Controller)
- Windows 10 (Domain-joined client)
- Active Directory Domain Services (AD DS)
- DNS and DHCP
- Group Policy Management
- NTFS and Share Permissions
- VirtualBox

## Environment Architecture
- Domain: lab.local
- Domain Controller: DC01
- Client Machine: PC01
- Organisational Units:
  - LAB-Users
  - LAB-Groups
  - LAB-Computers
- Security Groups:
  - GG-Finance
  - GG-HR

## Key Skills Demonstrated
- Active Directory user and group management
- Domain join and client configuration
- DNS and DHCP troubleshooting
- NTFS and share permission design (least privilege)
- Group Policy creation and scoping
- Mapped network drives via GPO
- Helpdesk-style incident troubleshooting
- ITIL-style ticket documentation

## Helpdesk Ticket Scenarios
All scenarios are documented in the `/tickets` folder:

1. Password Reset
2. Account Lockout
3. New Starter Provisioning
4. Leaver Deprovisioning
5. Permission Denied Troubleshooting
6. Group Policy Not Applying

Each ticket includes:
- Issue description
- Root cause analysis
- Resolution steps
- Verification

## Why This Lab Matters
This lab reflects real Tier 1 / Tier 2 helpdesk responsibilities and demonstrates practical experience resolving common enterprise IT issues rather than theoretical knowledge.

## Next Improvements
- PowerShell automation for user provisioning
- Additional Group Policy configurations
- Separate File Server (FS01) VM
- Centralised logging and monitoring
