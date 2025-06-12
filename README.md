# Windows Server 2012 R2 – Active Directory & Role Management Lab

This repository documents a hands-on lab. The lab involved configuring a Windows Server 2012 R2 environment in a virtual machine, performing system administration tasks such as user and group management, directory structuring, permission setting, and installing server roles.

## Lab Objectives

- Deploy and configure a Windows Server VM
- Build a directory tree structure using command-line tools
- Create and manage local users and groups
- Configure shared folder permissions based on group access
- Install and verify server roles (Web Server/IIS)

## Key Tasks

- **Deployed** a Windows Server 2012 R2 VM using VirtualBox with custom hardware specs
- **Renamed** the server to match the lab naming convention and documented the configuration setup
- **Built** a complete file and folder structure for a sample course (`MST100`) via the Command Prompt
- **Created** users and groups (e.g., Programmers, Athletes, Parking) and applied password policies, home directories, and account restrictions
- **Assigned** specific share permissions using group-based access control on the MST100 directory
- **Installed** the Web Server (IIS) role and **launched** the management interface to validate installation

## Screenshots

Screenshots of each step are stored in the `/screenshots` directory, including:
- Directory structure
  ![PartA](https://github.com/user-attachments/assets/cabe1810-e126-428a-a52c-4de55ceaefb3)

- User and group creation
  ![PartB2](https://github.com/user-attachments/assets/bace1927-9d5d-46d5-a04e-b266347471f0)

  ![PartB1](https://github.com/user-attachments/assets/7eefbf3e-e625-46cd-be1f-dd652b0dbf01)

- Permission settings
  ![PartB3](https://github.com/user-attachments/assets/dcae8e4a-ad53-4062-add6-b91965f26be6)

- Server role installation
  ![PartD](https://github.com/user-attachments/assets/4330dc00-f0a4-45a8-8651-a48c08e9e60f)


## Tools & Technologies

- VMware
- Windows Server 2012 R2
- Command Prompt
- Server Manager
- Active Directory tools (local user/group management)
- IIS (Internet Information Services)





