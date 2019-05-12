Ansible Role: Dovecot(pkg)
================================================================================
Insall Dovecot from a package

* Install Dovecot 2.2
* Deploy files into /etc/dovecot
* Open tcp/110, tcp/143, tcp/993, and tcp/995.

Requirements
--------------------------------------------------------------------------------
None.

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
dovecot:
...
```

Dependencies
--------------------------------------------------------------------------------
None. 

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-dovecot-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp/)
