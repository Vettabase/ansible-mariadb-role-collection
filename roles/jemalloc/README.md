# Jemalloc

This role installs and configures MySQL Server and MariaDB server to use Jemalloc as the default memory allocator.

## Requirements

Ansible version 2.12.6.

## Role Variables

None.

## Dependencies

None.

## Example Playbook
```
- hosts: dbservers
  become: true
  roles:
    - jemalloc
```
## Copyright and Contacts

This repository is distributed under the terms of the GNU GPL, version 3. Copyright: Vettabase Ltd.

To contact us

* info@vettabase.com
* https://vettabase.com

Maintainer: [Aldo Junior](https://github.com/aldoribeirojr)
