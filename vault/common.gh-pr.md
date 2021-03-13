---
id: common.gh-pr
title: Gh Pr
desc: ''
updated: 1615655543056
created: 1615655543056
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gh pr

> Manage GitHub pull requests from the command line.
> More information: <https://cli.github.com/manual/gh_pr>.

- Create a pull request:

`gh pr create`

- Check out a pull request locally:

`gh pr checkout {{pr_number}}`

- View the changes made in the PR:

`gh pr diff`

- Approve the pull request of the current branch:

`gh pr review --approve`

- Merge the pull request associated with the current branch, removing the branch on both the local and the remote:

`gh pr merge`

- Edit a pull request interactively:

`gh pr edit`

- Edit the base branch of a pull request:

`gh pr edit --base {{branch_name}}`
