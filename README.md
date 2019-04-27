Role Name
=========

[![Build Status](https://travis-ci.org/00willo/ansible-role_sublimetext.svg?branch=master)](https://travis-ci.org/00willo/ansible-role_sublimetext)

A role to install Sublime Text 3.

Requirements
------------

None.

Role Variables
--------------

The following variables are available:

```yaml
# Official Sublime Text release channel
release_channel: dev
```

The default is stable, and only the dev channel builds are available to licensed users.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: desktop
      roles:
         - { role: 00willo.sublimetext, release_channel: dev }
```

License
-------

MIT
