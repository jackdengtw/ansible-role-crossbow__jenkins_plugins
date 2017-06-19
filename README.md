Role Name
=========

A role to provide a idempotent way to manage jenkins plugins

Requirements
------------

None

Role Variables
--------------

jenkins_plugin_download_url

jenkins_home

jenkins_plugins


Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jackdengtw.crossbow__jenkins_plugins, tags: ["plugins"] }

License
-------

BSD

Author Information
------------------

Reference: https://github.com/jansenm/ansible-jenkins-roles/tree/master/jenkins/plugins
