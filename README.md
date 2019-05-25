PHPMYADMIN
=========

Deploy the phpmyadmin service running under the container via ansible.

Installation
------------

`ansible-galaxy install gengxiankun.phpmyadmin`

Requirements
------------

- CentOS 7.0+
- [Docker](https://github.com/gengxiankun-galaxy/docker)

Role Variables
--------------

| parameter | description |
| --------- | ----------- |
| PHPMYADMIN_PORT | Phpmyadmin external port |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - phpmyadmin

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
