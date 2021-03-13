---
id: linux.lsb_release
title: Lsb_release
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lsb_release

> Provides certain LSB (Linux Standard Base) and distribution-specific information.

- Print all available information:

`lsb_release -a`

- Print a description (usually the full name) of the operating system:

`lsb_release -d`

- Print only the operating system name (ID), suppressing the field name:

`lsb_release -i -s`

- Print the release number and codename of the distribution, suppressing the field names:

`lsb_release -rcs`
