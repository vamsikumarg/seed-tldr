---
id: linux.ipcrm
title: Ipcrm
desc: ''
updated: 1615655543103
created: 1615655543103
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# ipcrm

> Delete IPC (Inter-process Communication) resources.

- Delete a shared memory segment by ID:

`ipcrm --shmem-id {{shmem_id}}`

- Delete a shared memory segment by key:

`ipcrm --shmem-key {{shmem_key}}`

- Delete an IPC queue by ID:

`ipcrm --queue-id {{ipc_queue_id}}`

- Delete an IPC queue by key:

`ipcrm --queue-key {{ipc_queue_key}}`

- Delete a semaphore by ID:

`ipcrm --semaphore-id {{semaphore_id}}`

- Delete a semaphore by key:

`ipcrm --semaphore-key {{semaphore_key}}`

- Delete all IPC resources:

`ipcrm --all`
