frogy.centos7-nginx
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

none

Role Variables
--------------

hostname: mywordpress
wordpress_install_url: "http://{{ hostname }}/wp-admin/install.php?step=2"
blog_title: ANSIBLE_TEST
blog_user: admin
blog_password: admin
blog_email: foo@gmail.com

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
