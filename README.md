Role Name
=========

Configures /etc/hosts

Requirements
------------

None

Role Variables
--------------

````
---
# defaults file for ansible-etc-hosts
etc_hosts_static_ip: false  #defines if node has static IP.
````

Dependencies
------------

None

Example Playbook
----------------

#### GitHub
````
- hosts: all
  become: true
  vars:
  roles:
    - role: ansible-etc-hosts
  tasks:
````

#### Galaxy
````
- hosts: all
  become: true
  vars:
  roles:
    - role: mrlesmithjr.etc-hosts
  tasks:
````

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
