# k8s ops tools

[![Build Status](https://api.travis-ci.com/Xat59/ansible-role-k8sops.svg)](https://travis-ci.com/github/Xat59/ansible-role-k8sops) ![Apache 2.0 Licence](https://img.shields.io/hexpm/l/plug.svg) ![Ansible](https://img.shields.io/badge/ansible-2.10.x-green.svg)

Ansible role that installs Kubernetes tools for operators :

- [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/)
- [Kontena Lens](https://k8slens.dev/)

## Prerequisites

- ![ansible](https://img.shields.io/badge/ansible-2.10.x-green.svg)

## Usage

```yaml
- hosts: servers
  roles:
    - role: xat.k8sops
```

> Check the [defaults/main.yml](defaults/main.yml) file to see available variables.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/Xat59/ansible-role-k8sops/tags).

Additionaly you can see what change in each version in the [CHANGELOG.md](CHANGELOG.md) file.

## Authors

- **xat** - [xat](https://github.com/Xat59)
