---
title: GitFlow
tags: []
---

This work will mean in moments of conflict or in moments of agility.

I think it's quite a tool and we must understand that it's worth using no matter the size of a certain application or what style of work.

In my studies I captured some paragraphs and images that I found interesting for my knowledge.

Like this image from:

A successful Git branching model » nvie.com:

![Alt text](https://miro.medium.com/v2/resize:fit:828/1*8-zDz1s5Atux_yNW_mXmfg@2x.png "A successful Git branching model")

_The main branch will contain all the already tested, versioned code that will be delivered to the client and the develop branch is where all the workflow will take place before making the versioned release that will be merged into the master. The develop should always contain the most current code, where feature branches will be branched based on it._

There are some nomenclatures for creating new branches that will later be part of the develop branch or not.

**Feature**: for new implementations

**Bugfix**: to resolve issues, quickly and directly, from the develop branch

**Hotfix**: to resolve critical issue in production that cannot wait for new release

**Release**: to finalize the release and tags

With the _nomenclatures_ the command can be for example:

`git checkout -b feature/new-page`

First we must type what the purpose of the branch, and set a name for it (E.g. feature) and then what will be added or affected (E.g. new-page).
