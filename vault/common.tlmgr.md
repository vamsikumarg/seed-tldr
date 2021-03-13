---
id: common.tlmgr
title: Tlmgr
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# tlmgr

> Manages packages and configuration options of an existing TeX Live installation.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Install a package and its dependencies:

`tlmgr install {{package}}`

- Remove a package and its dependencies:

`tlmgr remove {{package}}`

- Display information about a package:

`tlmgr info {{package}}`

- Update all packages:

`tlmgr update --all`

- Show possible updates without updating anything:

`tlmgr update --list`

- Start a GUI version of tlmgr:

`tlmgr gui`

- List all TeX Live configurations:

`tlmgr conf`
