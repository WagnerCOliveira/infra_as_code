Dcoker
======

Instalação do Docker CE em Debian/CentOS.

Role Variables
--------------

- **packages_remove:** Pacotes para remover em ambas distribuições

Example Playbook
----------------

Including an example of how to use your role:

```yml
- hosts: docker
  become: yes
  roles:
  - docker
```
