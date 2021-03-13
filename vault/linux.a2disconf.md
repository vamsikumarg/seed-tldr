---
id: linux.a2disconf
title: A2disconf
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# a2disconf

> Disable an Apache configuration file on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2disconf.8.en.html>.

- Disable a configuration file:

`sudo a2disconf {{configuration_file}}`

- Don't show informative messages:

`sudo a2disconf --quiet {{configuration_file}}`
