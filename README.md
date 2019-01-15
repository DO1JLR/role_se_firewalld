 Ansible role to configure firewalld on SELINUX Server
--------------------------------------

### Features:

+ Allow HTTP(S) Traffic on Fedora Server
+ Allow reverse proxy (for nginx)
+ Allow PHP
+ Restart firewalld daemon


You can diable selinux by setting ``disable_selinux: true``.
But it is highly recomended to keep it activated and only configure what you realy need.

### Tested on:
 - Fedora 29 Server with SELINUX Policy enabled
