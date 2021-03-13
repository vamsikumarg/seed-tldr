---
id: windows.reg-export
title: Reg Export
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reg export

> Export the specified sub keys and values into a file.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-export>.

- Export all sub keys and values of a specific key:

`reg export {{key_name}} {{path/to/file.reg}}`

- Force overwriting of an existing file without prompt:

`reg export {{key_name}} {{path/to/file.reg}} /y`
