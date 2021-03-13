---
id: osx.date
title: Date
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# date

> Set or display the system date.

- Display the current date using the default locale's format:

`date +"%c"`

- Display the current date in UTC and ISO 8601 format:

`date -u +"%Y-%m-%dT%H:%M:%S%Z"`

- Display the current date as a Unix timestamp (seconds since the Unix epoch):

`date +%s`

- Display a specific date (represented as a Unix timestamp) using the default format:

`date -r 1473305798`
