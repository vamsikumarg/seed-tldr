---
id: common.lex
title: Lex
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lex

> Lexical analyser generator.
> Given the specification for a lexical analyser, generates C code implementing it.

- Generate an analyser from a Lex file:

`lex {{analyser.l}}`

- Specify the output file:

`lex {{analyser.l}} --outfile {{analyser.c}}`

- Compile a C file generated by Lex:

`cc {{path/to/lex.yy.c}} --output {{executable}}`
