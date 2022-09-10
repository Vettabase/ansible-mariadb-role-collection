# Chrony

This role installs and configures the Chrony time server (for time sincronization).


## Requirements

Ansible version 2.10.17.

No dependencies.


## Variables

A description of the settable variables for this role (defaults/main.yml).

| Variable           | Required | Description                 |
|--------------------|----------|-----------------------------|
| chrony_servers     | No       | The NTP list of servers     |
| chrony_package     | No       | Chrony package name         |
| chrony_service     | No       | NTP service name            |
| chrony_dir         | No       | chrony configuration dir    |
| chrony_filename    | No       | chrony configuration file   |


## Copyright and Contacts

This repository is distributed under the terms of the GNU GPL, version 3. Copyright: Vettabase Ltd.

To contact us

* info@vettabase.com
* https://vettabase.com

Maintainer: Federico Razzoli
