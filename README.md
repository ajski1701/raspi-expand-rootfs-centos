raspi-expand-rootfs-centos
=====================

An Ansible role for automatically expanding the root filesystem of a Raspberry Pi running CentOS.

Find it on [Ansible Galaxy](https://galaxy.ansible.com/AJ1701/raspi-expand-rootfs-centos/)!

Requirements
------------

* Requires growpart (which is pre-installed in CentOS 7 for Raspberry Pi!)

Role Variables
--------------

This role does not have any variables.

Dependencies
------------

This role does not have any dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: AJ1701.raspi-expand-rootfs-centos
          become: yes

License
-------
Charles Korns' license can be found in LICENSE.charleskorn.raspi-expanded-rootfs

A.J. Scgalski's license can be found in LICENSE

Author Information
------------------

Based off of the original Ansible playbook for Raspbian by Charles Korn ([me@charleskorn.com](me@charleskorn.com)). His original repository can be found at https://github.com/charleskorn/raspi-expanded-rootfs

Modified for CentOS 7 ARM by [A.J. Scgalski](https://github.com/AJ1701). Please see my GitHub account for my contact email.

Contributing
------------

Submit issues and pull requests on GitHub at [https://github.com/AJ1701/raspi-expand-rootfs-centos](https://github.com/AJ1701/raspi-expand-rootfs-centos).
