---
id: windows.reg-flags
title: Reg Flags
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reg flags

> Display or set flags on registry keys.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-flags>.

- Display current flags for a specific key:

`reg flags {{key_name}} query`

- Display help and available flag types:

`reg flags /?`

- Set specified space-separated flags, and unset unmentioned flags, for a specific key:

`reg flags {{key_name}} set {{flag_names}}`

- Set specified flags for a specific key and its sub keys:

`reg flags {{key_name}} set {{flag_names}} /s`
