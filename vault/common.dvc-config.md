---
id: common.dvc-config
title: Dvc Config
desc: ''
updated: 1615655543052
created: 1615655543052
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dvc config

> Low level command to manage custom configuration options for dvc repositories.
> These configurations can be on project, local, global, or system level.
> More information: <https://dvc.org/doc/command-reference/config>.

- Get the name of the default remote:

`dvc config core.remote`

- Set the project's default remote:

`dvc config core.remote {{remote_name}}`

- Unset the project's default remote:

`dvc config --unset core.remote`

- Get the config value for a specified key for the current project:

`dvc config {{key}}`

- Set the config value for a key on a project level:

`dvc config {{key}} {{value}}`

- Unset a project level config value for a given key:

`dvc config --unset {{key}}`

- Set a local, global, or system level config value:

`dvc config --local/global/system {{key}} {{value}}`
