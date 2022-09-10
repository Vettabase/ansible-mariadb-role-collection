# Chrony

This role installs and configures the Chrony time server (for time sincronization).


## Requirements

Ansible version 2.10.17.

No dependencies.


## Variables

A description of the settable variables for this role (defaults/main.yml).

| Variable           | Required | Description                            |
|--------------------|----------|----------------------------------------|
| chrony_servers     | No       | The NTP list of servers                |
| chrony_package     | No       | Chrony package name. OS-dependent      |
| chrony_service     | No       | NTP service name. OS-dependent         |
| chrony_dir         | No       | chrony configuration dirOS-dependent   |
| chrony_filename    | No       | chrony configuration fileOS-dependent  |

Where "OS-dependent" is specified, the variable default is 'DEFAULT'. If this value
is used, the role replaces it with a sensible default value, which depends on the
operating system.


## Copyright and Contacts

This repository is distributed under the terms of the GNU GPL, version 3. Copyright: Vettabase Ltd.

To contact us

* info@vettabase.com
* https://vettabase.com

Maintainer: Federico Razzoli
