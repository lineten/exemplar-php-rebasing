# Rebase 101

There are two rebasing exercises to complete. 

## Useful Reading

_Explanation and overview of rebasing_

[https://www.benmarshall.me/git-rebase/](https://www.benmarshall.me/git-rebase/)

_Comparison of rebasing and merging_

[https://slides.com/paul_melero/git-rebase#/21/0/0](https://slides.com/paul_melero/git-rebase#/21/0/0)

# Now complete the exercises below

> Don't be afraid to ask your line manager or a colleague for help completing these exercises


# EXERCISE 1

## Goals

You should end up with a single consolidated readme file - this will generate conflicts that need will resolving! 

In each of the branches you will find an edited readme with instructions for the rebase task. Complete each task using `rebase`, then `merge` these updated changes back to the trunk. Once complete submit a pull request to this repository and assign to your line manager for review!

## Instructions

Fork this repository to your personal GitHub account, this will copy all branches for you to work on locally, then complete the two tasks using the `rebase` command (see readme on each branch for details). When complete you should `merge` the TASK-X branches to the trunk branch. 

At the outset the branch tree looks like this:

![image](https://user-images.githubusercontent.com/248916/114893202-63200500-9e05-11eb-878d-62a5f4977ce6.png)

Once complete the tree should be a single linear commit history resembling that below

![image](https://user-images.githubusercontent.com/248916/114893411-94003a00-9e05-11eb-961b-dc0a13156cad.png)

The commit history should resemble the following

![image](https://user-images.githubusercontent.com/248916/114893685-de81b680-9e05-11eb-9ed1-85c0370f5c14.png)

# Add branch readme instruction segments (from merge conflicts) here:

_REMOVE_THIS_PLACEHOLDER_

# EXERCISE 2

Fork the repository below and follow the instructions. This time, once complete, share the forked repository with your line manager for review!

[https://github.com/lineten/exemplar-workshop-git-rebase](https://github.com/lineten/exemplar-workshop-git-rebase)




# Rebase 101

# squashing commits
This branch contains a number of commits that are very noisy, while useful during development, no value is offered by presering all these when merging back to the trunk branch therefore all of these commits should be combined into a single commit before submitting a PR# Rebase 101

# dropping commits
Mistakes happen, part of the code review should be to identity and potential errors or accidental disclosures that might happen during software development. This branch contains a commit that needs to be removed using the `drop` option, the remaining commits should be preserved using the `pick` option.