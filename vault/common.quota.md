---
id: common.quota
title: Quota
desc: ''
updated: 1615655543080
created: 1615655543080
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# quota

> Display users' disk space usage and allocated limits.

- Show disk quotas in human readable units for the current user:

`quota -s`

- Verbose output (also display quotas on filesystems where no storage is allocated):

`quota -v`

- Quiet output (only display quotas on filesystems where usage is over quota):

`quota -q`

- Print quotas for the groups of which the current user is a member:

`quota -g`

- Show disk quotas for another user:

`sudo quota -u {{username}}`
