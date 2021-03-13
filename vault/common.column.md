---
id: common.column
title: Column
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# column

> Format standard input or file into multiple columns.
> Rows are filled before columns; default separator is whitespace.

- Format output for a 30 characters wide display:

`printf "header1 header2\nbar foo\n" | column -c {{30}}`

- Split columns automatically and auto-align in a tabular format:

`printf "header1 header2\nbar foo\n" | column -t`

- Specify column delimiter character for the -t option (e.g. "," for csv); default is whitespace:

`printf "header1,header2\nbar,foo\n" | column -t -s{{,}}`

- Fill columns before filling rows:

`printf "header1\nbar\nfoobar\n" | column -c {{30}} -x`
