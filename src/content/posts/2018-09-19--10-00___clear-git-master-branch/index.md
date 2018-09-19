---
title: Clear a Git repository's master branch
categories:
  - dev
tags:
  - git
---

Sometimes there is a need to clear `master` branch of a Git repository. For example when you want to work with [Gatsby Starte Kit](https://github.com/greglobinski/gatsby-starter-kit) in the [Advanced way](https://greglobinski.github.io/gatsby-starter-kit-docs/advanced-usage/).

To achieve that delete the existing branch and create a brand new one pointing to a initial commit.

```bash
git branch -D master
git checkout -b master [initial-commit-hash]
```
