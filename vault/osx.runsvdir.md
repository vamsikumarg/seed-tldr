---
id: osx.runsvdir
title: Runsvdir
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# runsvdir

> Run an entire directory of services.

- Start and manage all services in a directory as the current user:

`runsvdir {{path/to/services}}`

- Start and manage all services in a directory as root:

`sudo runsvdir {{path/to/services}}`

- Start services in separate sessions:

`runsvdir -P {{path/to/services}}`
