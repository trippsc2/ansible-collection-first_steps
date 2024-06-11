<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.first_steps.debian
Version: 1.0.0

This role performs first steps on a freshly installed Debian system.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Debian | <ul><li>bullseye</li><li>bookworm</li></ul> |

## Dependencies

| Collection |
| ---------- |
| ansible.posix |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| debian_is_workstation | Whether the system is a workstation and should start a graphical environment. | bool | no |  | false |


## License
MIT

## Author and Project Information
Jim Tarpley
<!-- END_ANSIBLE_DOCS -->
