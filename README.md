# teams

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/teams)
[![General Workflow](https://github.com/rolehippie/teams/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/teams/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/teams/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/teams/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/teams/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/teams/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/teams)](https://github.com/rolehippie/teams/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.teams-blue)](https://galaxy.ansible.com/rolehippie/teams)

> [!IMPORTANT]
> This role have been archived because of the lack of maintenance and because
> we are not actively using it anymore. If you are using this role feel free
> to fork and maintain it on your own. Maybe we will unarchive this repository
> in the future at some point, maybe not... Who knows...

Ansible role to install unofficial teams client.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [teams_arch](#teams_arch)
  - [teams_package](#teams_package)
  - [teams_version](#teams_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### teams_arch

Architecture for the package

#### Default value

```YAML
teams_arch: amd64
```

### teams_package

Download URL for the package to install

#### Default value

```YAML
teams_package: https://github.com/IsmaelMartinez/teams-for-linux/releases/download/v{{
  teams_version }}/teams-for-linux_{{ teams_version }}_{{ teams_arch }}.deb
```

### teams_version

Version for the package

#### Default value

```YAML
teams_version: 1.3.8
```

## Discovered Tags

**_teams_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
