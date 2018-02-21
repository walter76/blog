---
layout: single
title:  "How to Work on a Branch with GitHub"
date:   2018-02-20 23:09:01 +0100
categories: git
---

1. Create the remote branch on github
1. Create a branch in the local repo
1. Set the remote branch as upstream branch with `git branch --set-upstream-to=origin/source source`. You can now use git pull/push to synchronize your work.
1. You can also pull/push the remote branch with `git pull origin source`
1. Switch branches with `git checkout <branch>`
1. List branches with `git branch -v`
1. Create branch with `git branch <branch>`
