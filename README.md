# Active Directory Home Lab

This project demonstrates a hands-on Active Directory lab built using Windows Server 2022 and Windows 11 in VMware Workstation.

## Lab Environment

- Windows Server 2022
- Windows 11
- VMware Workstation
- Domain: lab.local

## What I Configured

- Installed and configured Active Directory Domain Services (AD DS)
- Created the lab.local domain
- Created Organizational Units (OUs) for IT, HR, and Finance
- Created domain users and security groups
- Configured DNS for domain communication
- Joined a Windows 11 client to the domain
- Tested domain authentication
- Reset passwords, unlocked accounts, and enabled users
- Configured Group Policy restrictions for:
  - Control Panel
  - Command Prompt
  - Removable storage

## Testing and Verification

I verified the lab by:

- Logging in to Windows 11 using a domain account
- Using `whoami` to confirm domain authentication
- Testing Group Policy restrictions on the client machine
- Performing common Active Directory user administration tasks

## Screenshots

### Active Directory Users and Computers
![Control Panel Restriction](Screenshot%202026-08-12%20163755.png)

### Domain Login Verification
![CMD Restriction](Screenshot%202026-08-12%20163859%20-%20Copy.png)

### Control Panel Group Policy Restriction
![Active Directory](Screenshot%202026-08-12%20013952.png)

### Command Prompt Group Policy Restriction
![Domain Login](Screenshot%202026-08-12%20014046.png)

## Skills Practised

- Active Directory
- Windows Server Administration
- Group Policy
- DNS
- Domain Joining
- User and Group Administration
- Windows Troubleshooting
- VMware Workstation

## Future Improvements

I plan to continue expanding this lab with:

- Shared folders
- NTFS permissions
- Mapped network drives
- Password policies
- Account lockout policies
