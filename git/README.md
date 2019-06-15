---
layout: default
title: Git
has_children: true
permalink: /git
---


# Push folder to specific branch on remote

Useful for pushing folder to gh-pages.

Taken from: https://gist.github.com/cobyism/4730490

```
git subtree push --prefix ${folder} origin ${branch}
```
