---
id: common.gh-codespace
title: Gh Codespace
desc: ''
updated: 1642441815019
created: 1642441815019
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh codespace

> Connect and manage your codespaces in GitHub.
> More information: <https://cli.github.com/manual/gh_codespace>.

- Create a codespace in GitHub interactively:

`gh codespace create`

- List all available codespaces:

`gh codespace list`

- Connect to a codespace via SSH interactively:

`gh codespace ssh`

- Transfer a file to a codespace interactively:

`gh codespace cp {{path/to/source_file}} remote:{{path/to/remote_file}}`

- List the ports of a codespace interactively:

`gh codespace ports`

- Print the logs from a codespace interactively:

`gh codespace logs`

- Delete a codespace interactively:

`gh codespace delete`

- Display help for a subcommand:

`gh codespace {{subcommand}} --help`
