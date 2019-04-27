Role Name
=========

[![Build Status](https://travis-ci.org/00willo/ansible-role_sublimetext.svg?branch=master)](https://travis-ci.org/00willo/ansible-role_sublimetext)

A role to install Sublime Text 3.

Requirements
------------

None specifically.

I haven't tested directly against the various ansible versions, but it was tested against 2.5. However after doing a documentation review of the various ansible modules used, it should work fine on ansible >= 2.1

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

None

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
