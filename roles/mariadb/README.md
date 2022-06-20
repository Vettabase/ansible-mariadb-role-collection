# MariaDB

This role installs and configures MariaDB Server.

## Requirements

Ansible version 2.12.6.

## Role Variables

A description of the settable variables for this role (defaults/main.yml).

| Variable                | Required | Default | Choices                   | Comments                                 |
|-------------------------|----------|---------|---------------------------|------------------------------------------|
| mariadb_server_version  | no       | yes      | list                     | The MariaDB Server version               |


## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
    - hosts: dbservers
      become: true
      roles:
         - mariadb
```
## Copyright and Contacts

This repository is distributed under the terms of the GNU GPL, version 3. Copyright: Vettabase Ltd.

To contact us

* info@vettabase.com
* https://vettabase.com

Maintainer: [Aldo Junior](https://github.com/aldoribeirojr)