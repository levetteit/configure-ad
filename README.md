<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>
Active Directory Home Lab on Microsoft Azure

## Overview

This project documents the deployment and configuration of a Windows Active Directory home lab hosted in Microsoft Azure. The environment was built to gain hands-on experience with:

- Active Directory Domain Services (AD DS)
- Windows Server Administration
- Organizational Units (OUs)
- User and Group Management
- Domain Joining
- PowerShell Automation
- Windows Firewall Configuration
- Networking and Connectivity Testing
- Microsoft Azure Virtual Machines

The lab simulates a small enterprise environment using a Windows Server Domain Controller and a Windows 11 client machine connected to the domain.

---

# Technologies Used

- Microsoft Azure
- Windows Server
- Windows 11 Pro
- Active Directory Domain Services (AD DS)
- PowerShell
- Remote Desktop Protocol (RDP)
- Windows Defender Firewall

---

# Lab Environment

| Device | Role |
|---|---|
| DC-1 | Domain Controller |
| CLIENT-1 | Windows 11 Client |
| Azure Virtual Network | Internal Network Communication |

---

# Objectives

- Create and configure Azure Virtual Machines
- Configure a Domain Controller
- Install Active Directory Domain Services
- Create Organizational Units (OUs)
- Create and manage users
- Join a client machine to the domain
- Configure Windows Firewall settings
- Test internal network communication
- Automate user creation with PowerShell

---

# Deployment and Configuration Steps

## 1. Created Azure Virtual Machines

Created Windows Server and Windows 11 virtual machines inside Microsoft Azure.
>

---

# 2. Configured Windows Firewall

Disabled Windows Defender Firewall temporarily to allow internal lab communication and testing.

### Firewall Configuration
<p></p>
<img width="1672" height="941" alt="firewall-configuration jpg" src="https://github.com/user-attachments/assets/ebd75447-5a3c-4206-8b60-1f4f7f410550" />


---

# 3. Tested Network Connectivity

Verified communication between systems using PowerShell ping commands.

### Network Connectivity Test
<p></p>
<img width="1448" height="1086" alt="ping-test jpg" src="https://github.com/user-attachments/assets/4389e2b6-8150-42be-bd5c-2ad3a28e5e97" />


---

# 4. Installed Active Directory Domain Services

Installed the Active Directory Domain Services role using Server Manager.

### AD DS Installation
<p></p>
<img width="1448" height="1086" alt="ad-ds-installation" src="https://github.com/user-attachments/assets/80e2c171-493e-4fef-8bb3-137d590dd171" />


### Server Role Selection
<p></p>
<img width="1672" height="941" alt="server-role-selection" src="https://github.com/user-attachments/assets/a7faefb2-4cb3-4c50-9e09-bc170e1c2624" />


---

# 5. Created Organizational Units

Configured Organizational Units (OUs) inside Active Directory Users and Computers.

Created:
- _EMPLOYEES
- _ADMINS

### Organizational Units
<p></p>
<img width="1448" height="1086" alt="organizational-units" src="https://github.com/user-attachments/assets/678af4c3-932f-4c14-86ec-d41b742edc38" />


# 6. Created User Accounts

Created user accounts inside Active Directory.

### User Account Creation
<p></p>
<img width="1448" height="1086" alt="user-creation" src="https://github.com/user-attachments/assets/3ef4eae5-ff75-4a10-87be-0aca58bfe074" />


---

# 7. Joined Client Machine to Domain

Joined the Windows 11 client machine to the domain.

### Domain Join Configuration


---

# 8. Automated User Creation with PowerShell

Used PowerShell ISE to automate Active Directory user creation.

The script:
- Generated multiple user accounts
- Configured passwords
- Enabled accounts
- Added users into the Organizational Unit

### PowerShell Automation


---

# Skills Demonstrated

- Active Directory Administration
- Windows Server Management
- Azure Cloud Infrastructure
- Network Troubleshooting
- PowerShell Scripting
- User and Identity Management
- Domain Administration
- Virtual Machine Deployment
- Enterprise Environment Configuration

---

# Key Takeaways

This lab provided hands-on experience working with enterprise-level Windows infrastructure technologies commonly used in IT support, system administration, and cybersecurity environments.

The project strengthened my understanding of:
- Domain environments
- Identity and access management
- Windows networking
- System administration
- IT troubleshooting
- Automation using PowerShell

---

# Future Improvements

- Configure Group Policy Objects (GPOs)
- Add shared network folders
- Implement password policies
- Configure Remote Desktop Services
- Integrate osTicket with Active Directory
- Expand the environment with additional client machines

---

# Author

# Jerai Padilla
