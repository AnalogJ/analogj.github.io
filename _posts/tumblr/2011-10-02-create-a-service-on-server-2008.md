---
layout: post
title: Create a Service on Server 2008
date: '2011-10-02T00:00:00-07:00'
cover: '/assets/images/cover_microsoft.jpg'
subclass: 'post tag-post'
tags:
- Service
redirect_from:
- /post/41987394051/create-a-service-on-server-2008
- /post/41987394051
disqus_id: 'http://blog.thesparktree.com/post/41987394051'
categories: 'analogj'
navigation: True
logo: '/assets/logo-dark.png'

---
http://support.microsoft.com/kb/251192
How to create a service from an exe on server 2008

`sc create CustomUTorrent binPath= "D:\uTorrent\uTorrent.exe" start= boot start= auto error= ignore obj= <Domain\Username> password= <Password>`
