---
title: Getting Started
date: 2019-08-09 20:55:00 +0800
categories: [Blogging, Tutorial]
tags: [getting started]
seo:
  date_modified: 2020-03-30 07:34:39 +0800
---

## Preparation

Follow the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installtion of basic environment (Ruby, RubyGem, Bundler and Jekyll). In order to use the script tools to save time, we also need to install [Python](https://www.python.org/downloads/)(version 3.5 or abover) and [ruamel.yaml](https://pypi.org/project/ruamel.yaml/).

## To change the repo name..
First, change the repo name at Github. In local desktop, we have to let the local desktop to know that the repo name has been changed. Follow the instruction below.

```terminal
$ git remote -v
View existing remotes
origin  https://github.com/user/repo.git (fetch)
origin  https://github.com/user/repo.git (push)

$ git remote set-url origin https://github.com/user/repo2.git
Change the 'origin' remote's URL

$ git remote -v
Verify new remote URL
origin  https://github.com/user/repo2.git (fetch)
origin  https://github.com/user/repo2.git (push)
```
