---
id: common.wc
title: Wc
desc: ''
updated: 1615655543092
created: 1615655543092
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wc

> Count lines, words, or bytes.

- Count lines in file:

`wc -l {{file}}`

- Count words in file:

`wc -w {{file}}`

- Count characters (bytes) in file:

`wc -c {{file}}`

- Count characters in file (taking multi-byte character sets into account):

`wc -m {{file}}`

- Use standard input to count lines, words and characters (bytes) in that order:

`{{find .}} | wc`
