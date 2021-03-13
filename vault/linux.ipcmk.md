---
id: linux.ipcmk
title: Ipcmk
desc: ''
updated: 1615655543102
created: 1615655543102
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ipcmk

> Create IPC (Inter-process Communication) resources.

- Create a shared memory segment:

`ipcmk --shmem {{segment_size_in_bytes}}`

- Create a semaphore:

`ipcmk --semaphore {{element_size}}`

- Create a message queue:

`ipcmk --queue`

- Create a shared memory segment with specific permissions (default is 0644):

`ipcmk --shmem {{segment_size_in_bytes}} {{octal_permissons}}`
