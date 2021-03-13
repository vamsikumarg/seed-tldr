---
id: linux.deluser
title: Deluser
desc: ''
updated: 1615655543098
created: 1615655543098
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# deluser

> Delete a user from the system.
> Note: all commands must be executed as root.
> More information: <https://manpages.debian.org/adduser/deluser.8.html>.

- Remove a user:

`deluser {{username}}`

- Remove a user and their home directory:

`deluser --remove-home {{username}}`

- Remove a user and their home, but backup their files into a `.tar.gz` file in the specified directory:

`deluser --backup-to {{path/to/backup_directory}} --remove-home {{username}}`

- Remove a user, and all files owned by them:

`deluser --remove-all-files {{username}}`
