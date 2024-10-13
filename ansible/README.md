# Ansible Collection - jaquerespeis.libreDataCenter

Documentation for the collection.

# Development

Modify in your local ansible development location.

install local changes.
```
ansible-galaxy collection install ~/git/ansible_collections/jaquerespeis/libreDataCenter --force
```
Note: replace `~/git/ansible_collections/` with your local collection development path.

## Adding roles

We use molecule for role development and testing.
```
molecule init role <role_name> --driver-name docker
```
