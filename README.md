# Ansible Role: Tezos

Allow you to run a tezos node on the Alphanet.

## Requirements

It is required to run ansible 2.4.3 minimum.  
This role is currently tested and working on Debian 9, however it should work on all debian based distributions.

## Role Variables

`defaults/main.yml`

   tezos_create_user: true
   tezos_user: tezos
   tezos_install_dir: /opt/tezos

## Dependencies

None.

## Example Playbook

    - hosts: tezos-nodes
      roles:
        - { role: ansible-role-tezos }

## License

MIT / BSD

## Author Information

This role was created in 2018 by [merou](https://github.com/merou).
