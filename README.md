# Ansible Role: BTRFS

Installs BTRFS kernel and tools for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    # Reboot host if a new kernel has been installed
    allow_reboot: yes
    
    # Timeout before reboot
    reboot_timeout: 10

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - role: gaeldb.btrfs
          become: yes

## License

MIT / BSD

## Author Information

This role was created in 2023 by [Gael Barbier], founder of [Skalab](https://www.skalab.fr).
