Changelog
=========

v0.2.0
------

*Unreleased*

- Add Changelog. [ypid]

- Use ``debops.mariadb`` to allow to use MariaDB or MySQL on a remote server. [ypid]

- Updated to ownCloud 8.1. [ypid]

- Allow to use ``ooc`` via Ansible’s inventory. Can be used to enable apps and create users. [ypid]

- Setup shortcut for the `occ` command when not logged in as ``owncloud_user`` user and sudo allows it.
  Disabled by default. Can be enabled via ``owncloud_enable_occ_shortcut``. [ypid]
