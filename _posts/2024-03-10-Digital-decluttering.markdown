---
layout: post
title: "Digital Decluttering Moving to Jekyll From A Hosted Service"
date: 2024-03-10 2019 -0500
categories: knowledge management
---
The blog has now officially moved (hopefully for the last time) from the current host, Tumblr, to the home hosted on Github Pages via Jekyll. I have been admiring static site generators for what seems like forever though I was always frankly intimidated by the process. However, for my birthday this year, I took a day and decided to dig into [Jekyll](https://jekyllrb.com), [Homebrew](https://brew.sh), and [Ruby Gems](https://rubygems.org)[^1]. I spent the day installing and working my way through different tutorials. I had only heard of Homebrew and Ruby at that point and I wouldn't say I am much better now though I am more familiar with the Mac Terminal app. 

I then had the pleasure of trying to port over all my prior posts from [Blogger](https://www.blogger.com) and [Tumblr](https://www.tumblr.com)[^2], which I thought would be a manual process though the community has built several import tools that [work for a variety of different services](https://import.jekyllrb.com). The pages get imported just fine (albeit in HTML rather than Markdown), and they look fully integrated with the blog.

I do still have some issues with [deadlinks](https://en.wikipedia.org/wiki/Link_rot) though that is an issue on any website (large or small). I have found that I enjoy the service so far. It is more nuanced/fiddly to set up though it meets my needs, and I now have a text file for EVERY one of [my posts going back to 2008](%site.baseurl%{% post_url 2008-12-02-23-things-vol-1-blogging_4062 %}) so that is rather amazing considering everything. I am no longer locked into a single service. 

Here are some tutorial videos that I found helpful in working through Jekyll:

- [How to Install Homebrew on Mac](https://youtu.be/IWJKRmFLn-g?si=zG6ZOpl5YsRbZAX5)
- [Everything you need to know about Homebrew](https://youtu.be/kGFseTqdS0E?si=QTniXKjet4aM1J1R)
- [Building a Personal Website with GitHub Pages](https://www.youtube.com/live/q8MzWZRjRoU?si=CErZsif0X21v9HLm)
- [Making and hosting your personal website using Jekyll and Github pages](https://youtu.be/8NkxcaxRacA?si=Qxq5x8rg2wkJyA-w)

I still need to go through and update some links though I am pleased with how it all turned out. I also really appreciate being able to [host the site on GitHub Pages.](https://pages.github.com). The service sits atop the Github repository model so you only need to set up a repo, and then you can push commits to set up or update your site[^3].


[^3]: The system also has a great [help site](https://docs.github.com/en/pages), which always makes me like a service more. 
[^1]: It was a fun birthday in its way though not one I would have imagined myself taking a decade ago. 
[^2]: I had never even completed the port from Blogger to Tumblr when I moved more fully to that service sometime in 2019. 