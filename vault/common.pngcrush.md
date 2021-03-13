---
id: common.pngcrush
title: Pngcrush
desc: ''
updated: 1615655543079
created: 1615655543079
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pngcrush

> PNG image compression utility.
> More information: <https://pmt.sourceforge.io/pngcrush>.

- Compress a PNG file:

`pngcrush {{in.png}} {{out.png}}`

- Compress all PNGs and output to directory:

`pngcrush -d {{path/to/output}} *.png`

- Compress PNG file with all 114 available algorithms and pick the best result:

`pngcrush -rem allb -brute -reduce {{in.png}} {{out.png}}`
