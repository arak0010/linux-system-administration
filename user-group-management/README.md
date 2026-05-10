# Linux User and Group Management

## Objective
Create and manage users and groups on a Linux system to control access
and permissions.

## Environment
- Ubuntu 24.04 LTS (DigitalOcean Droplet)
- SSH key-based access from Windows PowerShell / Termius

## Tasks Performed
- Created a new Linux user
- Created a custom group
- Added the user to the group
- Verified group membership

## Commands Used
```bash
adduser testuser
groupadd itgroup
usermod -aG itgroup testuser
id testuser

