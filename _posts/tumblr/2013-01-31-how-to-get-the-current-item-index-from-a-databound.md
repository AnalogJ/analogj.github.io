---
layout: post
title: How to get the current Item index from a databound ListView
date: '2013-01-31T20:25:20-08:00'
cover: '/assets/images/cover_visual_studio.png'
subclass: 'post tag-post'
tags:
- ASP.Net
- C
redirect_from:
- /post/41986202792/how-to-get-the-current-item-index-from-a-databound
- /post/41986202792
disqus_id: 'http://blog.thesparktree.com/post/41986202792'
categories: 'analogj'
navigation: True
logo: '/assets/logo.png'

---
You can use `<%# Container.DisplayIndex %>` to get your position in the current list. You can use `Items.Count` on the `Control` to get the total `Item` count.
