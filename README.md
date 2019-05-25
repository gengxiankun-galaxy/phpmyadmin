PHPMYADMIN
=========

Deploy the phpmyadmin service running under the container via ansible.

Installation
------------

`ansible-galaxy install gengxiankun.phpmyadmin`

Requirements
------------

- [Docker](https://github.com/gengxiankun-galaxy/docker)

Role Variables
--------------

| parameter | description |
| --------- | ----------- |
| PHPMYADMIN_PORT | phpmyadmin external port |
| OPT_PATH | deployment service configuration directory |
| PHPMYADMIN_IMAGE | phpmyadmin docker image |

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
