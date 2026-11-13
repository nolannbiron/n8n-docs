---
title: Branch patterns
description: >-
  Understand the different relationships between n8n instances and Git branches
  that are possible with source control.
contentType: explanation
nodeTitle: Choose branching patterns
originalFilePath: source-control-environments/understand/patterns.md
originalUrl: 'https://docs.n8n.io/source-control-environments/understand/patterns'
url: >-
  https://docs.n8n.io/administer/use-source-control-and-environments/choose-branching-patterns
layout:
  description:
    visible: false
---

# Branch patterns <a href="#branch-patterns" id="branch-patterns"></a>

The relationship between n8n instances and Git branches is flexible. You can create different setups depending on your needs. 

{% hint style="info" %}
**Recommendation: don't push and pull to the same n8n instance**

You can push work from an instance to a branch, and pull to the same instance. n8n doesn't recommend this. To reduce the risk of merge conflicts and overwriting work, try to create a process where work goes in one direction: either to Git, or from Git, but not both.
{% endhint %}

## Multiple instances, multiple branches <a href="#multiple-instances-multiple-branches" id="multiple-instances-multiple-branches"></a>

This pattern involves having multiple n8n instances, each one linked to its own branch. 

You can use this pattern for environments. For example, create two n8n instances, development and production. Link them to their own branches. Push work from your development instance to its branch, do a pull request to move work to the production branch, then pull to the production instance.

The advantages of this pattern are:

* An added safety layer to prevent changes getting into your production environment by mistake. You have to do a pull request in GitHub to copy work between environments.
* It supports more than two instances.

The disadvantage is more manual steps to copy work between environments.

![Development and production n8n instances, each connected to its own Git branch, with a pull request moving work between the branches](../.gitbook/assets/vc-multi-multi.png)

## Multiple instances, one branch <a href="#multiple-instances-one-branch" id="multiple-instances-one-branch"></a>

Use this pattern if you want the same workflows, tags, and variables everywhere, but want to use them in different n8n instances. 

You can use this pattern for environments. For example, create two n8n instances, development and production. Link them both to the same branch. Push work from development, and pull it into production.

This pattern is also useful when testing a new version of n8n: you can create a new n8n instance with the new version, connect it to the Git branch and test it, while your production instance remains on the older version until you're confident it's safe to upgrade.

The advantage of this pattern is that work is instantly available to other environments when you push from one instance.

The disadvantages are:

* If you push by mistake, there is a risk the work will make it into your production instance. If you [use a GitHub Action to automate pulls](https://app.gitbook.com/s/wMJrGrimpx3PxCJpUswm/use-source-control-and-environments/tutorial-create-environments-with-source-control#optional-use-a-github-action-to-automate-pulls) to production, you must either use the multi-instance, multi-branch pattern, or be careful to never push work that you don't want in production.
* Pushing and pulling to the same instance can cause data loss as changes are overridden when performing these actions. You should set up processes to ensure content flows in one direction.

![Development and production n8n instances both connected to the same single Git branch](../.gitbook/assets/vc-multi-one.png)

## One instance, multiple branches <a href="#one-instance-multiple-branches" id="one-instance-multiple-branches"></a>

The instance owner can change which Git branch connects to the instance. The full setup in this case is likely to be a [Multiple instances, multiple branches](#multiple-instances-multiple-branches) pattern, but with one instance switching between branches.

This is useful to review work. For example, different users could work on their own instance and push to their own branch. The reviewer could work in a review instance, and switch between branches to load work from different users.

{% hint style="info" %}
**No cleanup**

n8n doesn't clean up the existing contents of an instance when changing branches. Switching branches in this pattern results in all the workflows from each branch being in your instance.
{% endhint %}

![One n8n instance switching between several Git branches to review work pushed by different users](../.gitbook/assets/vc-one-multi.png)

## One instance, one branch <a href="#one-instance-one-branch" id="one-instance-one-branch"></a>

This is the simplest pattern.

![Single n8n instance connected to a single Git branch](../.gitbook/assets/vc-one-one.png)

## Related resources

* [Use source control and environments](./)
* [Understand source control](understand-source-control.md)
* [Work with environments](work-with-environments.md)
* [Use Git in n8n](use-git-in-n8n.md)
* [Set up source control](set-up-source-control.md)
* [Push and pull changes](push-and-pull-changes.md)
* [Compare versions](compare-versions.md)
* [Move work between environments](move-work-between-environments.md)
* [Use environments programmatically with the public API](use-environments-via-api.md)
* [Tutorial: Create environments with source control](tutorial-create-environments-with-source-control.md)
