# selinux-local-modules
Custom local selinux modules, crafted by hand and machine, for debian buster kerberos ldap pam

this repository holds my custom selinux local modules.
 
# things to note

all local_* modules are generated through an iterative process and have not been reviewed.
I have since discovered that improperly labeled files and directories cause result in
incorrect allow rules when the denials are converted into allow rules via audit2allow.

php_fpm
-------

This is a custom module to support a domain for php_fpm
