Php gearman client
=========

Ansible role for installing php gearman client. Tested platforms are:
* Debian 8

Requirements
------------

Debian 8 (jessie)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

| Parameter | Required | Default | Choices | Comments |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| default_download_directory | yes | /tmp | | Sets directory where files will be downloaded |
| gearman_client_tarball_url | yes | https://pecl.php.net/get/gearman-1.1.2.tgz | | Sets php Gearman client tarball url |
| gearman_client_tarball_directory | yes | gearman-1.1.2 | | Sets php Gearman extract directory |


Dependencies
------------

None

Example 
----------------
    ---
    - hosts: all
      roles:
         - { role: antonchernik.php-gearman-client }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Anton Chernik](https://github.com/antonchernik).
