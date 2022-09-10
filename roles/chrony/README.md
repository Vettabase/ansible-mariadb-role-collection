# Chrony

This role installs and configures the Chrony time server (for time sincronization).


## Requirements

Ansible version 2.10.17.


## Role Variables

A description of the settable variables for this role (defaults/main.yml).

| Variable                | Required | Default | Choices                   | Comments                                 |
|-------------------------|----------|---------|---------------------------|------------------------------------------|
| ntp_servers             | no      | yes      | list                      | The NTP list of servers                  |
| chrony_package          | no      | yes      | eggs, spam                | The name of Chrony package               |
| chrony_service          | no      | yes      | eggs, spam                | The name of NTP service                  |
| chrony_dir              | no      | yes      | eggs, spam                | The Chrony directory                     |
| chrony_filename         | no      | yes      | eggs, spam                | The name of Chrony config filename       |


## Dependencies

None.


## Copyright and Contacts

This repository is distributed under the terms of the GNU GPL, version 3. Copyright: Vettabase Ltd.

To contact us

* info@vettabase.com
* https://vettabase.com

Maintainer: Federico Razzoli
