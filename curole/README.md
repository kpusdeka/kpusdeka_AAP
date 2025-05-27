Role Name
=========

This role will join the Linux Server to the Active Directory Domain based on a group in the inventory, or host group in Red Hat Satellite.
This will also allow you to login using your normal AD credentials.  The same that you would use to log into your PC.

Requirements
------------

This role will require the ansible fedora.linux_system_roles and possibly community.general.
If using ACTUAL red hat collections it would be 
- redhat.rhel_system_roles.ad_integration

Role Variables
--------------

There are no specific role variables that you need to use.

Dependencies
------------

ansible-galaxy collections install fedora.linux_system_roles
ansible-galaxy collection install community.general

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Andrew Meyer
