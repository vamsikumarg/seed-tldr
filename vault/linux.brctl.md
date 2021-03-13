---
id: linux.brctl
title: Brctl
desc: ''
updated: 1615655543096
created: 1615655543096
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# brctl

> Ethernet bridge administration.

- Show a list with information about currently existing ethernet bridges:

`sudo brctl show`

- Create a new ethernet bridge interface:

`sudo brctl add {{bridge_name}}`

- Delete an existing ethernet bridge interface:

`sudo brctl del {{bridge_name}}`

- Add an interface to an existing bridge:

`sudo brctl addif {{bridge_name}} {{interface_name}}`

- Remove an interface from an existing bridge:

`sudo brctl delif {{bridge_name}} {{interface_name}}`
