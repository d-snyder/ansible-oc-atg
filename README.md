Role Name
=========

This role installs oracle atg 11.1 on linux platforms

Requirements
------------

You must accept the license agreement, download V46005-01.zip (for the linux x64 platform), and copy it to the playbook directory or to the files directory within this role from: https://edelivery.oracle.com


Role Variables
--------------

install_root: the root directory where the application will be installed. Actual installation may occur within a path under this directory depending on the installer.
install_url: If defined, the role will attempt to download the install archive before attempting installation.


Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: oc-atg, install_root: /opt/oracle, sudo_user: oracle }
         

License
-------

GPL V3

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
