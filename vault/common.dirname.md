---
id: common.dirname
title: Dirname
desc: ''
updated: 1615655543051
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dirname

> Calculates the parent directory of a given file or directory path.

- Calculate the parent directory of a given path:

`dirname {{path/to/file_or_directory}}`

- Calculate the parent directory of multiple paths:

`dirname {{path/to/file_a}} {{path/to/directory_b}}`

- Delimit output with a NUL character instead of a newline (useful when combining with `xargs`):

`dirname --zero {{path/to/directory_a}} {{path/to/file_b}}`
