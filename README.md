# Samba installation and configuration
Usage:
```
ansible-playbook main.yml
```
## Features/Tasks
- samba server installation on smbserver host
- samba client installation on smbclients hosts
- samba server configuration
  - smb.conf preparation
  - creating system users for smbclients
  - creating smb users for smbclients
- samba clients configuration [WIP]

## !WIP!
Currently supported (and tested) samba server host is Debian 11.  
Currently supported (and tested) samba client host is AlmaLinux 8.
