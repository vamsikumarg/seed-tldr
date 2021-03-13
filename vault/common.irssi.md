---
id: common.irssi
title: Irssi
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# irssi

> Text based IRC client.
> More information: <https://irssi.org>.

- Open irssi and connect to a server with a nickname:

`irssi -n {{nickname}} -c {{irc.example.com}}`

- Open irssi and connect with a specific server on a given port:

`irssi -c {{irc.example.com}} -p {{port}}`

- View the help:

`irssi --help`

- Join a channel:

`/join {{#channelname}}`

- Change active window (starts at 1):

`/win {{window_number}}`

- Exit the application cleanly and quitting any server(s):

`/quit`
