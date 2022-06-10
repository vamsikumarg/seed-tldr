---
id: linux.file
title: File
desc: ''
updated: 1623965306222
created: 1623965306222
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# file

> Determine file type.

- Give a description of the type of the specified file. Works fine for files with no file extension:

`file {{filename}}`

- Look inside a zipped file and determine the file type(s) inside:

`file -z {{foo.zip}}`

- Allow file to work with special or device files:

`file -s {{filename}}`

- Don't stop at first file type match; keep going until the end of the file:

`file -k {{filename}}`

- Determine the mime encoding type of a file:

`file -i {{filename}}`
