mapr_accounts
=========

Set up MapR user accounts.

Requirements
------------

Role Variables
--------------

```
mapr_user: mapr
mapr_group: mapr
mapr_home: /home/mapr

# Password generated with openssl passwd -1
mapr_user_pw: '$1$rtVcRI.q$CvXXArvDBT0zb1uEuXE1e/'

mapr_uid: 2147483632
mapr_gid: 2147483632
```


Dependencies
------------


Example Playbook
----------------

    - hosts: all
      roles:
         - { role: mapr_accounts, mapr_user: mapr }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
