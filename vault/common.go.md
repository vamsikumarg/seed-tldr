---
id: common.go
title: Go
desc: ''
updated: 1615655543060
created: 1615655543060
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# go

> Tool for managing go source code.
> More information: <https://golang.org>.

- Download and install a package, specified by its import path:

`go get {{package_path}}`

- Compile and run a source file (it has to contain a `main` package):

`go run {{file}}.go`

- Compile a source file into a named executable:

`go build -o {{executable}} {{file}}.go`

- Compile the package present in the current directory:

`go build`

- Execute all test cases of the current package (files have to end with `_test.go`):

`go test`

- Compile and install the current package:

`go install`

- Initialize a new module in the current directory:

`go mod init {{module_name}}`
