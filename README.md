hostname
========

Set hostname via Ansible hostname module and updates /etc/hosts with hostname and domain.

Requirements
------------

Ansible version 1.4 with modules _hostname_ and _template_. Ansible module _hostname_ currently implemented on only Debian, Ubuntu, RedHat and CentOS.

Role Variables
--------------

 * _hostname_name_ - new hostname (not FQDN, before first dot)
 * _hostname_domain_ - new domain name

License
-------

MIT

Author Information
------------------

Sergey Korolev (<korolev.srg@gmail.com>)
