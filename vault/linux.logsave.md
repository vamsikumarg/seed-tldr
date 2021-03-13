---
id: linux.logsave
title: Logsave
desc: ''
updated: 1615655543104
created: 1615655543104
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# logsave

> Save the output of a command in a logfile.
> More information: <https://linux.die.net/man/8/logsave>.

- Execute command with specified argument(s) and save its output to log file:

`logsave {{path/to/logfile}} {{command}}`

- Take input from standard input and save it in a log file:

`logsave {{logfile}} -`

- Append the output to a log file, instead of replacing its current contents:

`logsave -a {{logfile}} {{command}}`

- Show verbose output:

`logsave -v {{logfile}} {{command}}`
