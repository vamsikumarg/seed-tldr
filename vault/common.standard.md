---
id: common.standard
title: Standard
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# standard

> The JavaScript Standard Style tool for linting and fixing JavaScript code.
> More information: <https://standardjs.com>.

- Lint all JavaScript source files in the current directory:

`standard`

- Lint specific JavaScript file(s):

`standard {{path/to/file(s)}}`

- Apply automatic fixes during linting:

`standard --fix`

- Declare any available global variables:

`standard --global {{variable}}`

- Use a custom ESLint plugin when linting:

`standard --plugin {{plugin}}`

- Use a custom JS parser when linting:

`standard --parser {{parser}}`

- Use a custom ESLint environment when linting:

`standard --env {{environment}}`
