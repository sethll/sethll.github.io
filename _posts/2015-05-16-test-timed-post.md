---
date: 2015-05-16
layout: post
title: Test of timed release
tags: test
---

I read that Jekyll is capable of making future posts. Testing whether a 
specific timestamp is needed or if it auto-posts at midnight. 

## Followup (2015-05-18)

The built-in future posting feature of Jekyll is pretty neat, I am glad that
the feature exists. To enable post queuing, all you need to do is disable 
posts with a future date from being published. 

In your config.yml file, enter: 

    future: false

. . . and you are all set. In your front-matter, enter your desired publish 
date. The front matter for this page (which was written on 2015-05-14) reads 
thus: 

    ---
    date: 2015-05-16
    layout: post
    title: Test of timed release
    tags: test
    ---

You can even set a specific time (with specific time zone) for the publication
to go live. 

    date: 2015-05-16 09:00 +0600

