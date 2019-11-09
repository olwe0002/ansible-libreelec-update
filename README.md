# general

This is a ansible role to upgrade your [libreelec](https://libreelec.tv/) to the in the group vars specified version. Additionally the [kodinerds](https://github.com/kodinerds/repo) repo is installed. This needs to be activated in the Kodi gui manually.

# how to use

1. change the variables in the inventory/group_vars/{libreelec,all} files.
2. change the inventory/hosts file

After that you can run it with the command `ansible-playbook playbooks/libreelec.yml`


