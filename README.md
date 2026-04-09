
# Active Directory Lab Project - Step-by-Step Guide

This is my guide that teaches you what Active Directory is, what it's used for, and how to set up an environment that automates the bulk creation of over 10,000 users. 
This guide demonstrates how to organize those users into organizational units, and configure the accounts via Group Policy.

## What This Guide Is For
Goal: Set up an Active Directory environment, create and configure a domain, use PowerShell to generate over 10,000 users, organize the accounts into organizational units (OUs), and apply Group Policy objects to manage user settings and permissions.<br>
Target Audience: IT students, system administrators, or beginner learners in Windows Server and Active Directory.<br> 
Estimated time: 1-5 hours (depending on experience level)

Environments and Technologies Used

- VirtualBox
- Windows Server
- Active Directory Domain Services (AD DS)
- PowerShell

## What is Active Directory?

Active Directory (AD) is a Microsoft database that connects users with all of the network resources they need to get their work done. It stores the information of users, passwords, and devices. This allows administrators to manage the permissions and access to resources from one central location.

It allows administrators to:
- Create and manage user accounts
- Control access to files and systems
- Enforce security policies using Group Policy
- Organize resources using Organizational Units (OUs)

## What is Active Directory used for?

Active Directory (AD) is a system used by many organizations to manage users, computers, and their resources in one place. It runs on local servers, and controls what users can access through permissions. Active directory improves security, simplifies user and device management, and can scale to thousands of users. 

Installation & Setup Steps

### 1 - Install Active Directory Domain Services 
1. Log into your Windows Server VM.
2. Click on Server Manager.
3. Click Add Roles and Features.
4. Select Active Directory Domain Services (AD DS).
5. Install the role.
6. After the installation is done, click on “Promote this server to a domain controller.”
7. Create a new forest (example: qclouted.local).
  

### 2 - Create Organizational Units (OUs)
Open Active Directory Users and Computers.
Right-click your domain (lab.local).
Select New → Organizational Unit.
Create these OUs:
Sales
IT
HR
Finance



### 3 - Create Bulk Users with PowerShell 
1. Type in PowerShell in the Windows Search bar located on the bottom left of the screen.
2. Right click on PowerShell, and click "Run as administrator."
3. Click on the link below, and follow the instructions in the document. https://docs.google.com/document/d/1_3BeYu5J2PcIoxjmSKD9ya60L0NzdNTGK9vevE_I7zY/edit?usp=sharing


### 4 - 


---


---


---



---


---

## Skills Demonstrated

- Active Directory administration
- PowerShell scripting
- Automation at scale
- IT infrastructure setup
