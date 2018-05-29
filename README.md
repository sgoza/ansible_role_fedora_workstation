# ansible_role_fedora_workstation
Setup Fedora workstation

1. Create playbook:
---

- name: Setup Fedora Workstation
  hosts: localhost
  tasks:
    - include_role:
       name: ansible_role_fedora_workstation

2. Run command: ansible-playbook fedora_workstation.yaml -b -K --become-method=su
