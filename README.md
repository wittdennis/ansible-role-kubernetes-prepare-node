# wittdennis.kubernetes_prepare_node

Ansible role to prepare a host to run kubernetes workload

## Role Variables

```yaml
kubernetes_prepare_node_disable_selinux: true # controls if selinux should be disabled
```

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: wittdennis.kubernetes_prepare_node }

## License

MIT
