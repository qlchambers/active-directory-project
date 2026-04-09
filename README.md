
# Active Directory Lab Project - Step-by-Step Guide

This is my guide that teaches you how to set up and test a VPN inside a Windows 10 virtual machine on Azure.
This guide demonstrates how to install Proton VPN, connect, and verify your VPN connection.
## What This Guide Is For

Goal: Set up an Active Directory environment, create and configure a domain, use PowerShell to generate over 10,000 users, organize the accounts into organizational units (OUs), and apply Group Policy objects to manauge user settings and permissions. 
Target Audience: IT students, system administrators, or beginner learners in Windows Server and Active Directory.
Estimated time: 1-5 hours (depending on experience level)


- Setting up an Active Directory environment
- Generating and importing 10,000+ users
- Automating account creation using PowerShell
- Organizing users into OUs

## What is Active Directory?

Active Directory (AD) is a Microsoft database that connects users with all of the network resources they need to get their work done. It stores the information of users, passwords, and devices. This allows administrators to manage the permissions and access to resources from one central location.

It allows administrators to:
- Create and manage user accounts
- Control access to files and systems
- Enforce security policies using Group Policy
- Organize resources using Organizational Units (OUs)

## What is Active Directory used for?

Active Directory (AD) is a system used by many organizations to manage users, computers, and their resources in one place. It runs on local servers, and controls what users can access through permissions. Active directory improves security, simplifies user and device management, and can scale to thousands of users. 


---


---

## Environments and Technologies Used

- VirtualBox
- Windows Server
- Active Directory Domain Services (AD DS)
- PowerShell

---

## Steps Overview

1. Install Active Directory Domain Services
2. Promote server to Domain Controller
3. Create Organizational Units
4. Generate user data (CSV)
5. Bulk create users using PowerShell
6. Verify users in Active Directory

---

## Result

Successfully created and managed over 10,000 user accounts using automation.

---

## Skills Demonstrated

- Active Directory administration
- PowerShell scripting
- Automation at scale
- IT infrastructure setup
