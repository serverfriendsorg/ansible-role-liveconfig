# Ansible Role: ansible-role-liveconfig

An Ansible Role that installs the [Liveconfig.com](https://www.liveconfig.com/en) webhosting panel.

In addition it installs further php interpreters and the lcsam (Liveconfig Spamassasin Filter).

Also the role installs the liveconfig-meta package which
installs liveconfig with a LAMP package (Apache, MySQL/MariaDB, Postfix)

## Requirements

None

## Dependencies

None

## Supported OS

Supported are currently Debian, Ubuntu, CentOS and SUSE.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Example Playbook

    - hosts: liveconfig
      roles:
        - ansible-role-liveconfig

## License

GNU General Public License v3.0

## Author Information

This role was created in 2020 by [Steven Conrad Bayer](https://steven.serverfriends.org/).
