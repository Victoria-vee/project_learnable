# project_learnable

<hr>

## Version Control

Version control is the process of tracking and managing changes made to software code. It is typically done with version control systems which are tools that automates version controls.

<hr>

## Difference between git and github

- git is a distributed version control system that tracks changes to source code over time WHILE github is a web-based hosting platform for git repositories.

- git is a local repository that track changes locally WHILE github provides a platform for collaboration on repositories online.

- git is a software WHILE git is a service.

<hr>

## Other github alternatives

- GitLab

- Bitbucket

- launchpad

<hr>

## Difference between git fetch and git pull

- git fetch downloads changes from the remote repository without merging it into the local directory WHILE git pull downloads changes made in the remote repository into the local directory.

- We can review and confirm metch using git fetch and then git merch WHILE in git pull, we cannot review changes because it automatically merges the changes.

- git fetch only updates the remote repository without updating the local repository while git pull updates both the remote repository and local repository.

<hr>

## git rebase

Git rebase allows the user to take all changes committed on one branch and replays them on a different branch. Basically, its like cutting your commits and pasting them on a different branch.


```$ git checkout new_feature```

```$ git rebase main```

<hr>

## git cherry-pick

Git cherry-pick is a command that allows developers select commits from one branch and appending it to annother. The coomits a selected with the commits hash(SHA).

```$ git cherry-pick <SHA>```
