<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.first_steps.rhel
Version: 1.0.0

This role performs first steps on a freshly installed RHEL-based system.

## Requirements

| Platform | Versions |
| -------- | -------- |
| EL | <ul><li>8</li><li>9</li></ul> |

## Dependencies

| Collection |
| ---------- |
| ansible.posix |
| community.general |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| rhel_red_hat_username | Red Hat subscription username. Required for RHEL only. | str | no |  |  |
| rhel_red_hat_password | Red Hat subscription password. Required for RHEL only. | str | no |  |  |
| rhel_subscription_auto_attach | Auto attach subscription. Required for RHEL only. | bool | no |  | false |
| rhel_subscription_syspurpose_usage | System purpose usage. Required for RHEL only. | str | no |  |  |
| rhel_subscription_syspurpose_service_level_agreement | System purpose service level agreement. Required for RHEL only. | str | no |  |  |
| rhel_subscription_syspurpose_sync | System purpose sync. Required for RHEL only. | bool | no |  | false |
| rhel_subscription_pool | Subscription pool. Required for RHEL only. | str | no |  |  |


## License
MIT

## Author and Project Information
Jim Tarpley
<!-- END_ANSIBLE_DOCS -->
