correcthorse.postgresql
=========

Role for installing a postgresql application stream/profile.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

| Variable				| Default			| Notes						|
| :---            | :---				| :---						|
| postgresql_version  | 10  | Should be a valid RHEL stream version |
| postgresql_profile: | "server"  | "client" or "server"  |

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

* [Josh Rusch](https://correct.horse/)
