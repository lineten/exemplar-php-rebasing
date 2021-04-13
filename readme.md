# Rebase 101

This repo contains a number of branches - these should be rebased prior to opening a PR back to the trunk, each branch will contain at least one conflict and a number of other commits that must be incorporated into the version history correctly 

## Useful Reading

_Explanation and overview of rebasing_

[https://www.benmarshall.me/git-rebase/](https://www.benmarshall.me/git-rebase/)

_Comparison of rebasing and merging_

[https://slides.com/paul_melero/git-rebase#/21/0/0](https://slides.com/paul_melero/git-rebase#/21/0/0)

# Goals

In each of the branches you will find an edited readme with instrcutions for the rebase task, pleae complete these steps and open a PR back to the trunk

# squashing commits
This branch contains a number of commits that are very noisy, while useful during development, no value is offered by presering all these when merging back to the trunk branch therefore all of these commits should be combined into a single commit before submitting a PR

# dropping commits
Mistakes happen, part of the code review should be to identity and potential errors or accidental disclosures that might happen during software development. This branch contains a commit that needs to be removed using the `drop` option, the remaining commits should be preserved using the `pick` option.
