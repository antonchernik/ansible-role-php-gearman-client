Php gearman client
=========

Ansible role for installing php gearman client. Tested platforms are:
* Debian 8
* Debian 9
* Ubuntu 16

Requirements
------------

Debian 8 (jessie)
Debian 9 (stretch)
Ubuntu 16 (xenial)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

| Parameter | Required | Default | Choices | Comments |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| default_download_directory | yes | /tmp | | Sets directory where files will be downloaded |
| gearman_client_tarball_url | yes | https://github.com/wcgallego/pecl-gearman/archive/master.tar.gz | | Sets php Gearman client tarball url |
| gearman_client_tarball_directory | yes | pecl-gearman-master | | Sets php Gearman extract directory |


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
