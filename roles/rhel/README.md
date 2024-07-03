<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.first_steps.rhel
Version: 1.0.5

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
| rhel_red_hat_username | <p>Red Hat subscription username.</p><p>Required for RHEL only.</p> | str | no |  |  |
| rhel_red_hat_password | <p>Red Hat subscription password.</p><p>Required for RHEL only.</p> | str | no |  |  |
| rhel_subscription_auto_attach | <p>Auto attach subscription.</p><p>Required for RHEL only.</p> | bool | no |  | false |
| rhel_subscription_syspurpose_usage | <p>System purpose usage.</p><p>Required for RHEL only.</p> | str | no |  |  |
| rhel_subscription_syspurpose_service_level_agreement | <p>System purpose service level agreement.</p><p>Required for RHEL only.</p> | str | no |  |  |
| rhel_subscription_syspurpose_sync | <p>System purpose sync.</p><p>Required for RHEL only.</p> | bool | no |  | false |
| rhel_subscription_pool | <p>Subscription pool.</p><p>Required for RHEL only.</p> | str | no |  |  |


## License
MIT

## Author and Project Information
Jim Tarpley
<!-- END_ANSIBLE_DOCS -->
