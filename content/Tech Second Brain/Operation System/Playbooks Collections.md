---
title: OS Playbooks Collections
tags:
  - ansible
  - ansible-playbooks
  - linux
---
# Setup General VM

>[!summary]
>Ansible Playbooks for general config VM

```yaml title="general-setup.yaml"
---
- name: Update and install packages from apt repository
  become: true
  tags: update_and_install
  block:
    - name: Update via apt
      ansible.builtin.shell:
        cmd: |
          sudo apt update &&
          sudo apt upgrade -y
      changed_when: false

    - name: Install docker.io and docker-compose
      ansible.builtin.apt:
        name:
          - docker.io
          - docker-compose
        state: present

    - name: Install jq
      ansible.builtin.apt:
        name:
          - jq
        state: present

    - name: Install postgresql-client
      ansible.builtin.apt:
        name:
          - postgresql-client
        state: present
```