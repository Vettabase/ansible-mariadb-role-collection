# Chrony
=========
This role installs and configures the Chrony time server (for time sincronization).

## Requirements
------------

Ansible version 2.12.6.

## Role Variables
--------------

A description of the settable variables for this role (defaults/main.yml).

| Variable                | Required | Default | Choices                   | Comments                                 |
|-------------------------|----------|---------|---------------------------|------------------------------------------|
| ntp_servers             | no      | yes      | list                      | The NTP list of servers                  |
| chrony_package          | no      | yes      | eggs, spam                | The name of Chrony package               |
| chrony_service          | no      | yes      | eggs, spam                | The name of NTP service                  |
| chrony_dir              | no      | yes      | eggs, spam                | The Chrony directory                     |
| chrony_filename         | no      | yes      | eggs, spam                | The name of Chrony config filename       |

## Dependencies
------------

None.

## Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - chorny

## License
-------

BSD

## Author Information
------------------

This role was written by [Aldo Junior](https://github.com/aldoribeirojr) to be used in the configuration of a Chrony server on a database server.