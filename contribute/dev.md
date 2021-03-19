---
title: 开发指南
description: 经纬wiki搭建指南
published: true
date: 2021-03-19T12:43:52.192Z
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
4. Realize Chinese search(Baidu search need a whu domain).
5. Database backup.
6. Monitor new illegal comments and visualization(py sql).
7. Comments reply somebody.
8. Subtitle super link.
