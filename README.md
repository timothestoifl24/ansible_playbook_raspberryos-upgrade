# Raspberry Pi Debian Upgrade Playbook

This playbook upgrades Raspberry Pi hosts from Debian Bookworm to Trixie and optionally performs firmware upgrades.

## Structure
- `playbook.yml`: Main playbook
- `vars.yml`: Contains release versions
- `roles/os-upgrade.yml`: Handles the OS upgrade
- `roles/firmware-upgrade.yml`: Handles firmware updates (optional)
- `ansible.cfg`: Ansible configuration

## Usage

```bash
ansible-playbook playbook.yml --ask-become-pass
