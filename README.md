# new-nginx-vhost
Ansible role to create directories, copy template files, and perform all other prerequisite tasks to create a new Nginx virtual host.

## Usage
```bash
ansible-playbook example-playbook.yml --ask-become-pass
```

## Requirements
1. Nginx deployment on one or more servers that uses sites-available and sites-enable directories.
1. Single host or host group defined in your Ansible hosts file.
