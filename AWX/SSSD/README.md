# Dependence
Playbook created for use in Ansible 2.8.2 and AWX 6.1.0.0

It is mandatori create input variables for ` {{ Sysadmin }} ` and ` {{ AllowLogon }} ` in AWX.

`Sysadmin` => Used by groups that need Super User permission (not used by global AD Administrators Group) to access the server.

`AllowLogon` => Used by ssh login (not Super User permission) to access the server.
