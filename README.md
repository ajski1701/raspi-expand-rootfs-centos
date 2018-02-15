raspi-expand-rootfs-centos
=====================

An Ansible role for automatically expanding the root filesystem of a Raspberry Pi running CentOS.

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

AJ1701's license can be found in LICENSE.AJ1701.raspi-expand-rootfs-centos

Author Information
------------------

Based off of the Ansible playbook by Charles Korn ([me@charleskorn.com](me@charleskorn.com)). His original repository can be found at https://github.com/charleskorn/raspi-expanded-rootfs

Modified for CentOS 7 ARM by [AJ1701](https://github.com/AJ1701)

Contributing
------------

Submit issues and pull requests on GitHub at [https://github.com/AJ1701/raspi-expand-rootfs-centos](https://github.com/AJ1701/raspi-expand-rootfs-centos).
