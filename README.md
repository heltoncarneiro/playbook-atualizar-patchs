# Ansible Playbooks - Atualização de Servidores

Este repositório contém playbooks Ansible para atualização automática de servidores Linux.

## Playbooks

- apt-update.yml → Atualização para Debian/Ubuntu
- zypper-update.yml → Atualização para SUSE/Opensuse

## Uso

```bash
ansible-playbook -i inventory/hosts playbooks/apt-update.yml