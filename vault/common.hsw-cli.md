---
id: common.hsw-cli
title: Hsw CLI
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# hsw-cli

> The command line REST tool for the Handshake wallet.
> More information: <https://npmjs.com/package/hs-client>.

- Unlock the current wallet (timeout in seconds):

`hsw-cli unlock {{passphrase}} {{timeout}}`

- Lock the current wallet:

`hsw-cli lock`

- View the current wallet's details:

`hsw-cli get`

- View the current wallet's balance:

`hsw-cli balance`

- View the current wallet's transaction history:

`hsw-cli history`

- Send a transaction with the specified coin amount to an address:

`hsw-cli send {{address}} {{1.05}}`

- View the current wallet's pending transactions:

`hsw-cli pending`

- View details about a transaction:

`hsw-cli tx {{transaction_hash}}`
