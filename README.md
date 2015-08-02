Karspexet-ansible
=======

Kårspexet  Public Ansible Configuration

To simulate a run, use --check

`ansible-playbook -i inventory site.yml --check` or `make check`

To limit it to a specific host or group, do:

`ansible-playbook -i inventory site.yml --check -l biljett.karspexet.se`

or

`ansible-playbook -i inventory site.yml --check -l biljett-servers`

To run this for real, just remove "--check".

To run on all servers, type `make install`.
