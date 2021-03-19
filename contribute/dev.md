---
title: 开发指南
description: 经纬wiki搭建指南
published: true
date: 2021-03-19T03:56:29.892Z
tags: 
editor: markdown
dateCreated: 2021-03-17T07:31:38.446Z
---

# How to contribute code

## Technique

Use [wiki-js](https://github.com/Requarks/wiki) as main application, other services are:
  - docker
  - git
  - PostgreSQL
  - aliyun oss

## Deploy

1. Buy a domain, or apply a subdomain of [sgg.whu.wdu.cn](https://www.sgg.whu.edu.cn).
2. Deploy wiki and postgres with docker.
3. Configure email and ssl.
4. install git lfs and ossutil.

## Todo

1. Use git hooks to auto deploy images.
2. Add analyse.
3. Integeate whu sso, or whu email register.
4. Realize Chinese search.
5. Database backup.
