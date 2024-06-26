
Install FortiSwitch Ansible Galaxy
==================================

This document explains how to install the FortiSwitch Ansible Galaxy
Collection.

--------------

Install Python3
~~~~~~~~~~~~~~~

-  Follow steps in https://www.python.org/ to install Python3 on your
   host.

Install Ansible Core
~~~~~~~~~~~~~~~~~~~~

-  Follow instructions in
   https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
   to install Ansible
-  The Ansible core version requirement: >= 2.15.0

Install FortiSwitch Galaxy Collection
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The FortiSwitch Ansible Galaxy will support multilple FortiSwitch major releases,
you can install the latest collection by default via command
``ansible-galaxy collection install fortinet.fortiswitch``. you can also
choose another galaxy version to match your FortiSwitch device.

Please see the `versionig notes`_ for more recently released collections
and install the ones which are marked ``latest`` for your devices.

.. _versionig notes: version.html

