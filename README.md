# Ansible Role fuse-overlayfs

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role fuse-overlayfs and may depend of other roles and plugins of the library.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## Example

### Playbook

```
---

- hosts: localhost
  roles:
    - buildah
    - fuse-overlayfs
  vars:
    fuse_overlayfs_build_mode: container
    fuse_overlayfs_version: v0.7.7
```

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2020 - David Fischer
