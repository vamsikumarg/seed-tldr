---
id: linux.scanimage
title: Scanimage
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# scanimage

> Scan images with the Scanner Access Now Easy API.
> More information: <http://sane-project.org/man/scanimage.1.html>.

- List available scanners to ensure the target device is connected and recognized:

`scanimage -L`

- Scan an image and save it to a file:

`scanimage --format={{pnm|tiff|png|jpeg}} > {{path/to/new_image}}`
