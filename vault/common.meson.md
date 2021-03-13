---
id: common.meson
title: Meson
desc: ''
updated: 1615655543069
created: 1615655543069
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# meson

> SCons-like build system that uses python as a front-end language and Ninja as a building backend.
> More information: <https://mesonbuild.com>.

- Generate a c project with a given name and version:

`meson init --language={{c}} --name={{myproject}} --version={{0.1}}`

- Configure builddir with default values:

`meson setup {{build_dir}}`

- Build the project:

`meson compile -C {{path/to/build_dir}}`

- Show the help:

`meson --help`

- Show version info:

`meson --version`
