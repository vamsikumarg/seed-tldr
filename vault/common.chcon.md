---
id: common.chcon
title: Chcon
desc: ''
updated: 1623965306176
created: 1623965306176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chcon

> Change SELinux security context of a file or files/directories.
> More information: <https://www.gnu.org/software/coreutils/chcon>.

- View security context of a file:

`ls -lZ {{path/to/file}}`

- Change the security context of a target file, using a reference file:

`chcon --reference={{reference_file}} {{target_file}}`

- Change the full SELinux security context of a file:

`chcon {{user}}:{{role}}:{{type}}:{{range/level}} {{filename}}`

- Change only the user part of SELinux security context:

`chcon -u {{user}} {{filename}}`

- Change only the role part of SELinux security context:

`chcon -r {{role}} {{filename}}`

- Change only the type part of SELinux security context:

`chcon -t {{type}} {{filename}}`

- Change only the range/level part of SELinux security context:

`chcon -l {{range/level}} {{filename}}`
