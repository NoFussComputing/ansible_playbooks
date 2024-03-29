---
title: Ansible Playbooks
description: No Fuss Computings Ansible Playbooks
date: 2023-05-27
template: project.html
about: https://gitlab.com/nofusscomputing/projects/ansible/ansible_playbooks
---

!!! Note
    Docs Still under development

The playbooks in this repository are included in our [Ansible Execution Environment](../../execution_environment/index.md) docker container.

Available Playbooks:

1. [awx.yaml](awx.md) 

1. [backup.yaml](backup/index.md)

1. [common.yaml](common.md)

1. [git_configuration.yaml](git_configuration.md)

1. [glpi.yaml](glpi.md)

1. [keycloak.yaml](keycloak.md)

1. [mariadb.yaml](mariadb.md)

1. [postgresdb.yaml](postgresdb.md)

1. [restore.yaml](restore/index.md)

1. Direct Module Access

    These playbooks allow the direct calling of an Ansible module.

    1. [ansible_module_mysql.yaml](modules/mysql.md)

    1. [ansible_module_postgres.yaml](modules/postgres.md)


## Docs ToDo

- notate usage/inclusions within ansible-ee image
- notate gitlab-ci jobs etc
- notate playbook variables prefix must be `nfc_pb_`
