---
layout: single
title:  "How to Work on a Branch with GitHub"
date:   2018-02-20 23:09:01 +0100
categories: git
---

In this post I will show how to create a branch if your repository is on GitHub
and what you have to do to synchronize it with your local repository.

# Create the Remote Branch on GitHub

First you need to create a remote branch on GitHub. This branch is afterwards
used to synchronize with your local repository.

Go to GitHub and open the repository that you would like to create the branch.
In the first tab you can switch between branches and there is also the place
where you can create a new one.

![Create a Branch on GitHub]({{ "/assets/github-create-branch.png" | absolute_url }})

Enter a branch name in the field, e.g. some-fix, and hit enter. The branch will
be created from your current branch.

# Create a Branch in Your Local Repository

Now you need a branch in your local repository. This branch is created by
`git checkout -b some-fix`.

![Create a Branch in Local Repository]({{ "/assets/git-create-branch-locally.png" | absolute_url }})

# Set the Remote Branch as Upstream Branch

Now we need to tell git that we would like to synchronize this branch with the
branch on GitHub. This is done by setting the remote branch as upstream branch.
You can do this with `git branch --set-upstream-to=origin/source source`. You
can now use git pull/push to synchronize your work.

You can also pull/push the remote branch with `git pull origin source`

# Switch Branches

You can switch branches locally with `git checkout <branch>`. If you want to
switch to a new branch and create it automatically use
`git checkout -b <branch>`.

# List Branches

You can list all your branches with `git branch -v`.

# Create Branches

Branches are created with `git branch <branch>`.

# Delete Branches

After you have finished working on that branch it is time to remove it. You can
do this with `git branch -d <branch>`.
