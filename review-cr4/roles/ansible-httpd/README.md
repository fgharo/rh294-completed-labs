ansible-httpd
=========

Example ansible-httpd role from "Red Hat Enterprise Linux Automation with Ansible" (RH294)


Requirement
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

* `web_package`: the RPM package
* `web_service`: the systemd service
* `web_config_file`: the path to the main configuration file
* `web_root`: the path to an index.html file
* `web_fw_service`: the name of a firewalld service


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - ansible-httpd



License
-------

BSD

Author Information
------------------
Red Hat (training@redhat.com)
