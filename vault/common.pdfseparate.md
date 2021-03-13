---
id: common.pdfseparate
title: Pdfseparate
desc: ''
updated: 1615655543077
created: 1615655543077
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pdfseparate

> Portable Document Format (PDF) file page extractor.
> More information: <https://manpages.debian.org/unstable/poppler-utils/pdfseparate.1.en.html>.

- Extract pages from PDF file and make a separate PDF file for each page:

`pdfseparate {{path/to/source_filename.pdf}} {{path/to/destination_filename-%d.pdf}}`

- Specify the first/start page for extraction:

`pdfseparate -f {{3}} {{path/to/source_filename.pdf}} {{path/to/destination_filename-%d.pdf}}`

- Specify the last page for extraction:

`pdfseparate -l {{10}} {{path/to/source_filename.pdf}} {{path/to/destination_filename-%d.pdf}}`
