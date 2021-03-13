---
id: windows.reg-unload
title: Reg Unload
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reg unload

> Remove data from the registry that was loaded using the `reg load` command.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-unload>.

- Remove data from the registry for a specified key:

`reg unload {{key_name}}`
