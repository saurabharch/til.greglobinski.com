---
title: Clear mastser branch
categories:
  - dev
tags:
  - git
---

https://stackoverflow.com/questions/15454555/how-can-i-completely-empty-the-master-branch-in-git

```bash
git branch -D master
git checkout -b master <initial commit hash>
This will create a totally new master branch unrelated to whatever you had:

git branch -D master
git checkout --orphan master
git rm -rf *
```
