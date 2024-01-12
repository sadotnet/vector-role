Role Name
=========

Deploy Vector using ansible.


Requirements
------------

- Ansible >= 2.7 


Role Variables
--------------

name default_value
vector_version "0.33.1"
vector_config_template "templates/vector.toml.j2"
vector_config "/etc/vector/vector.toml"

Example Playbook
----------------

---
- hosts: all
  roles:
  - vector-role


License
-------
BSD

