---
id: linux.opkg
title: Opkg
desc: ''
updated: 1615655543106
created: 1615655543106
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# opkg

> A lightweight package manager used to install OpenWrt packages.

- Install a package:

`opkg install {{package}}`

- Remove a package:

`opkg remove {{package}}`

- Update the list of available packages:

`opkg update`

- Upgrade all the installed packages:

`opkg upgrade`

- Upgrade one or more specific package(s):

`opkg upgrade {{package(s)}}`

- Display information for a specific package:

`opkg info {{package}}`

- List all the available packages:

`opkg list`
