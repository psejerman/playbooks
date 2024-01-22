# Playbooks for basic server configuration

## Supported distributions:
- Debian 12 (Bookworm)

## Prerequisites
- Configuered ssh server on the target machine
- Installed sudo package
- non-administrative user account with the permissions to use sudo command (see manuals about sudoers file)

## Notes
Entrypoint is the main.yml file. After installing the ansible package on the control host it can be executed via:

```bash
ansible-playbook main.yml --ask-become-pass
```
