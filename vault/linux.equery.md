---
id: linux.equery
title: Equery
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# equery

> View information about Portage packages.

- List all installed packages:

`equery list '*'`

- Search for installed packages in the Portage tree and in overlays:

`equery list -po {{package_name}}`

- List all packages that depend on a given package:

`equery depends {{package_name}}`

- List all packages that a given package depends on:

`equery depgraph {{package_name}}`

- List all files installed by a package:

`equery files --tree {{package_name}}`
