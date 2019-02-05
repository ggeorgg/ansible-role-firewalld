firewalld
=========

This role uses firewalld to apply firewall rules to a Red Hat 7 or Cent OS 7 system.


Role Variables
--------------

    firewalld_default_zone: "public"

    firewalld_allowed_services:
      - ssh
    firewalld_allowed_ports: []
    firewalld_allowed_forward_ports: []
    firewalld_rich_rules: []

**Note:** any services or ports not specified in the variables will be disabled.


License
-------

MIT

Author Information
------------------

Brian O'Reilly / Merchant Lynx Services
