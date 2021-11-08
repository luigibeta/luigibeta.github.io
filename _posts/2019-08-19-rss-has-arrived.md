---
title: RSS is finally here!
excerpt: Yes, it's finally here. The OFFICIAL Luigi Beta Blog RSS feed has arrived.
date: 2019-08-19T14:29:30
author: Samplasion
hidden: false
layout: post
image: /assets/images/rss-has-arrived.png
---

Yes, it's finally here. The OFFICIAL Luigi Beta Blog RSS feed has arrived. You can do pretty much whatever you want with it.  

* You want to setup a webhook? _**You can.**_
* You want to read the posts from your favorite feed reader? _**You can.**_
* You want to eat lasagne with your frend Bobbie? _**You can.**_

In fact, the webhook in **#blog-posts** in the [dev server](https://invite.gg/luigi) is using the RSS to fire a webhook with IFTTT (or Zapier, ask tee for details).  

To whoever wants technical details, this feed uses the `rss` npm module to easily build a feed from JavaScript. I mean, we could've used our own methods, but why reinvent the wheel? npm is there for this reason.  
[You can access the RSS feed by clicking the link in the blog home, or by clicking here](/blog/rss.xml).