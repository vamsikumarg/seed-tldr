---
id: common.git-submodule
title: Git Submodule
desc: ''
updated: 1615655543059
created: 1615655543059
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# git submodule

> Inspects, updates and manages submodules.
> More information: <https://git-scm.com/docs/git-submodule>.

- Install a repository's specified submodules:

`git submodule update --init --recursive`

- Add a Git repository as a submodule:

`git submodule add {{repository_url}}`

- Add a Git repository as a submodule at the specified directory:

`git submodule add {{repository_url}} {{path/to/directory}}`

- Update every submodule to its latest commit:

`git submodule foreach git pull`
