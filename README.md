# Ansible Role FUSE OverlayFS

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role FUSE OverlayFS and may depend of other roles and plugins of the library.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## Example

### Playbook

Install from source:

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

Install from a release:

```
---

- hosts: localhost
  roles:
    - buildah
    - fuse-overlayfs
  vars:
    fuse_overlayfs_setup_mode: release
```

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2022 - David Fischer
