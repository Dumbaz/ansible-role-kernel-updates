Role Name
=========

A brief description of the role goes here.

Requirements
------------

* Grub2 is in use
* the following CLI tools: awk, grep, [needs-restarting](http://man7.org/linux/man-pages/man1/needs-restarting.1.html)

Role Variables
--------------

The variable `desired_kernel_version` should be set to your desired kernel version. As an example, I have the line `desired_kernel_version: 3.10.0-693.21.1.el7` in my group_vars for a server group.

Dependencies
------------

No dependencies to other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible-role-kernel-updates

License
-------

MIT, CC-BY

Author Information
------------------

Shoot me an email.
