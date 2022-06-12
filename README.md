lighthouse-role
=========

Download and install Lighthouse

Requirements
------------

—
Role Variables
--------------

lighthouse_repo: "https://github.com/VKCOM/lighthouse.git"
lighthouse_dir: "/lighthouse"

Dependencies
------------

- buluma.git
- nginxinc.nginx

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- hosts: servers
  roles:
     - { role: lighthouse-role }
```
License
-------

BSD

Author Information
------------------

Alexey Khrapov,  Netology, devops-13
