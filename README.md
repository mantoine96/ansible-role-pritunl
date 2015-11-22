Pritunl VPN Role
=========

This role allows for easy installation of the VPN Server [Pritunl](https://pritunl.com).

The installation is possible on :
1. Ubuntu (Precise (14.04) and Trusty (12.04))
2. Debian (Jessie (8) or Wheezy (7))
3. CentOS (7)
4. Fedora (22)
5. RHEL (7)
6. Amazon Linux (2013.03) (SOON)


Requirements
------------

There isn't any requirement to this role.

Dependencies
------------

There aren't any dependencies to this role.
Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
  - { role: thehunt33r.pritunl}
```
License
-------

BSD

Feel free to contribute, open issues, etc... Indeed I do not consider this role final yet. It lacks configurability.
