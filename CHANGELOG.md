# Changelog

All notable changes to this project will be documented in this file.

## [1.0.11] - 2025-01-08

- Added Changelog.
- Updated collection README documentation.

## [1.0.10] - 2024-09-10

- *trippsc2.first_steps.rhel* role - Removed the `rhel_subscription_pool` variable, as this is deprecated.

## [1.0.9] - 2024-09-06

- *trippsc2.first_steps.rhel* role - Added `no_log` option to `rhel_red_hat_password` variable.

## [1.0.8] - 2024-08-09

- Minimum Ansible version changed from `2.14` to `2.15` due to EOL status.

## [1.0.7] - 2024-07-08

- Updated manifest file to ensure that molecule tests are not included in releases.

## [1.0.6] - 2024-07-07

- *trippsc2.first_steps.debian* role - Removed steps to set the machine to a graphical target.
- *trippsc2.first_steps.debian* role - Added the `debian_install_firewalld` and `debian_install_ssl_cert` variables to allow steps to install `firewalld` and `ssl-cert` pacakges to be enabled/disabled (enabled by default).
- *trippsc2.first_steps.ubuntu* role - Removed steps to set the machine to a graphical target.
- *trippsc2.first_steps.ubuntu* role - Added the `ubuntu_install_ssl_cert` variable to allow step to install `ssl-cert` pacakge to be enabled/disabled (enabled by default).

## [1.0.5] - 2024-07-03

- *trippsc2.first_steps.ubuntu* role - Added step to install the `ssl-cert` package.

## [1.0.4] - 2024-07-03

- *trippsc2.first_steps.debian* role - Added step to install the `ssl-cert` package.

## [1.0.3] - 2024-07-02

- *trippsc2.first_steps.debian* role - Added step to install the `gnupg` package.
- *trippsc2.first_steps.ubuntu* role - Added step to install the `gnupg` package.

## [1.0.2] - 2024-06-30

- *trippsc2.first_steps.debian* role - Updated documentation and role metadata for readability.
- *trippsc2.first_steps.rhel* role - Updated documentation and role metadata for readability.
- *trippsc2.first_steps.ubuntu* role - Updated documentation and role metadata for readability.
- *trippsc2.first_steps.ubuntu* role - Added step to remove the `unattended-upgrades` package that caused problems with Vagrant boxes.

## [1.0.1] - 2024-06-13

- *trippsc2.first_steps.debian* role - Updated documentation and role metadata for readability.
- *trippsc2.first_steps.rhel* role - Updated documentation and role metadata for readability.
- *trippsc2.first_steps.rhel* role - Removed step to install the `python36` package on EL 8.
- *trippsc2.first_steps.ubuntu* role - Updated documentation and role metadata for readability.

## [1.0.0] - 2024-06-11

- Initial release.
- *trippsc2.first_steps.debian* role - Role added.
- *trippsc2.first_steps.rhel* role - Role added.
- *trippsc2.first_steps.ubuntu* role - Role added.
