---
id: common.sbt
title: Sbt
desc: ''
updated: 1615655543084
created: 1615655543084
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# sbt

> Build tool for Scala and Java projects.
> More information: <https://www.scala-sbt.org/1.0/docs/index.html>.

- Start the SBT interactive shell (REPL):

`sbt`

- Create a new Scala project from an existing Giter8 template hosted on GitHub:

`sbt new {{scala/hello-world.g8}}`

- Use the specified version of sbt:

`sbt -sbt-version {{version}}`

- Use a specific jar file as the sbt launcher:

`sbt -sbt-jar {{path}}`

- List all sbt options:

`sbt -h`
