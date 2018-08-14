# Install Gentoo on a rootserver
This role can install Gentoo with a software raid1, encrypted, lvm on a
rootserver.

## Sample playbook
```
---
- hosts: all
  user: root
  roles:
  - gentoo_on_server
```

## Run the playbook
```
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i fqdn.example.com, sample_playbook.yml
```
