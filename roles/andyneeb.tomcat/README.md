Role Name
=========

Installs Tomcat WebServer on RHEL/CentOS

Requirements
------------

Requires JVM.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    java_version: 1.8.0

    tomcat_version: 8.5.42

    tomcat_http_port: 8080

    tomcat_https_port: 8443

    tomcat_admin_username: admin

    tomcat_admin_password: admin


Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: tomcat_server
  roles:
     - role: andyneeb.tomcat
       become: yes
```

License
-------

Apache 2.0

Author Information
------------------

This role was created by Andreas Neeb in 2019.
