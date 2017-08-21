# Homework 1

This homework will prepare me for basic setup for the course.

## Basic course setup

##### **Slack**

![Slack](./imagens/slack-profile.png)

##### **Github**

[Link para o repositório](https://github.com/matheuslins/if1004-DevOps)

## Learning Git

Completed all course except the advance themes.

![Gitbranching](./imagens/git.png)

## Hooks

```shell
#!/usr/bin/env python

import webbrowser

webbrowser.open ("https://github.com/matheuslins/if1004-DevOps")

```

![post-commit](./imagens/hooks.gif)

## Concepts

#### **In your own words, explain the difference between continuous integration, continuous delivery, and continuous deployment.**

**Continuos integration**

Continuos integration is a methodology witch the code team merging code to a central repository many time a day. Before each merge, generally into master, triggers an automated build and testing sequence. The new codes are build on stage after pass all unit testing and another's checks that depends on the complexity of the project.

**Continuos delivery**

Continuous deployment is a practice of automating delivery software release process. It’s a second step. After CI plus automatically prepare and track a release to production. The ideal implementation is that anyone with sufficient power to deploy a new release, any time, with one or a few clicks.

**Continuous deployment**

Continuous deployment is a process that any changes are deployment without explicit approval from any developer. In other words, is a fully automated deployment to production.

#### **How does DevOps team model (e.g., site reliability engineer) differ than a a NoOps team model (e.g. Netflix team)? What differences in architecture allow for a NoOps model?**


#### **Explain the principle of Every Feature is an Experiment**


#### **Be Fast to Deploy but Slow (or Slower) to Release**
