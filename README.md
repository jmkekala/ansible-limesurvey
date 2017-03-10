Limesurvey
=========

Installs the Open Source on-line survey application Limesurvey on http://host/limesurvey .

Requirements
------------

Working Mariadb/Mysql installation with www-server

Example Playbook
----------------

```
- name: Limesurvey
  hosts: all
  sudo: yes

  roles:
    - limesurvey
```

License
-------

BSD

Author Information
------------------

original author: Thomas.Berton@UGent.be
modified by: juha.kekalainen@gmail.com