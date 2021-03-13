---
id: linux.slapt-get
title: Slapt Get
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# slapt-get

> An apt like system for Slackware package management.
> Package sources need to be configured in the slapt-getrc file.

- Update the list of available packages and versions:

`slapt-get --update`

- Install a package, or update it to the latest available version:

`slapt-get --install {{package_name}}`

- Remove a package:

`slapt-get --remove {{package_name}}`

- Upgrade all installed packages to their latest available versions:

`slapt-get --upgrade`

- Locate packages of interest by the package name, disk set, or version:

`slapt-get --search {{package_name}}`

- Show information about a package:

`slapt-get --show {{package_name}}`
