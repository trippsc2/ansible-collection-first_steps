# Changelog

All notable changes to this project will be documented in this file.

## [1.1.3] - 2025-06-10

### Collection

- Changed repository URL to use GitHub Organization.

## [1.1.2] - 2025-05-16

### Role - debian

- Removed `bullseye` from metadata.

### Role - fedora

- Added `all` versions to metadata.

### Role - rhel

- Reordered versions in metadata.

### Role - ubuntu

- Reordered versions in metadata.

## [1.1.1] - 2025-01-10

### Role - fedora

- Fixed path to `/etc/dnf/dnf.conf` config file.

## [1.1.0] - 2025-01-10

### Collection

- *fedora* role added.

## [1.0.11] - 2025-01-08

### Collection

- Added Changelog.
- Updated collection README documentation.

## [1.0.10] - 2024-09-10

### Role - rhel

- Removed the `rhel_subscription_pool` variable, as this is deprecated.

## [1.0.9] - 2024-09-06

### Role - rhel

- Added `no_log` option to `rhel_red_hat_password` variable.

## [1.0.8] - 2024-08-09

### Collection

- Minimum Ansible version changed from `2.14` to `2.15` due to EOL status.

## [1.0.7] - 2024-07-08

### Collection

- Updated manifest file to ensure that molecule tests are not included in releases.

## [1.0.6] - 2024-07-07

### Role - debian

- Removed steps to set the machine to a graphical target.
- Added the `debian_install_firewalld` and `debian_install_ssl_cert` variables to allow steps to install `firewalld` and `ssl-cert` pacakges to be enabled/disabled (enabled by default).

### Role - ubuntu

- Removed steps to set the machine to a graphical target.
- Added the `ubuntu_install_ssl_cert` variable to allow step to install `ssl-cert` pacakge to be enabled/disabled (enabled by default).

## [1.0.5] - 2024-07-03

### Role - ubuntu

- Added step to install the `ssl-cert` package.

## [1.0.4] - 2024-07-03

### Role - debian

- Added step to install the `ssl-cert` package.

## [1.0.3] - 2024-07-02

### Role - debian

- Added step to install the `gnupg` package.

### Role - ubuntu

- Added step to install the `gnupg` package.

## [1.0.2] - 2024-06-30

### Role - debian

- Updated documentation and role metadata for readability.

### Role - rhel

- Updated documentation and role metadata for readability.

### Role - ubuntu

- Updated documentation and role metadata for readability.
- Added step to remove the `unattended-upgrades` package that caused problems with Vagrant boxes.

## [1.0.1] - 2024-06-13

### Role - debian

- Updated documentation and role metadata for readability.

### Role - rhel

- Updated documentation and role metadata for readability.
- Removed step to install the `python36` package on EL 8.

### Role - ubuntu

- Updated documentation and role metadata for readability.

## [1.0.0] - 2024-06-11

### Collection

- Initial release.
- *debian* role added.
- *rhel* role added.
- *ubuntu* role added.
