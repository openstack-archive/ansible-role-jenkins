====================
ansible-role-jenkins
====================

Ansible role to manage Jenkins

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-jenkins.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-jenkins
* Bugs: https://bugs.launchpad.net/ansible-role-jenkins

Description
-----------

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install jenkins
      hosts: jenkins
      roles:
        - ansible-role-jenkins
