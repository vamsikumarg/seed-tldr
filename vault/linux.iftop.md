---
id: linux.iftop
title: Iftop
desc: ''
updated: 1615655543102
created: 1615655543102
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# iftop

> Show bandwidth usage on an interface by host.
> More information: <https://linux.die.net/man/8/iftop>.

- Show the bandwidth usage:

`sudo iftop`

- Show the bandwidth usage of a given interface:

`sudo iftop -i {{interface}}`

- Show the bandwidth usage with port information:

`sudo iftop -P`

- Do not show bar graphs of traffic:

`sudo iftop -b`

- Do not look up hostnames:

`sudo iftop -n`

- Get help about interactive commands:

`?`
