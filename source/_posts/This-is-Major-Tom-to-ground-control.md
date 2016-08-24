---
title: This is Major Tom to ground control
date: 2016-08-23 22:57:34
tags:
    - hexo
    - blog
---
Engines Ready! It is Time to liftoff!

Welcome to my blog. Here I will try to post interesting pieces of my own work such as sysadmin scripts, useful dev tools with examples, etc. I hope you will enjoy the lecture of my website while you learn new concepts.

First of all. How is this blog made?

I'm using [Hexo](https://hexo.io/) as blogging platfform. I found it few days ago and it seems really useful and easy to use. Following the [documentation](https://hexo.io/docs/) this blog was set in few minutes.

The feature I like the most is that you can mantain the blog in your system (in my case I'm using an Ubuntu 16.04 VM) for writting posts. When the post is ready to be published you only have to "build" the blog and "deploy" it to your site repo. Hexo will generate a static website in the previously choosen repository (it is all in the [documentation](https://hexo.io/docs/)).

So, when I've finished this post, from my VM, I check that the post is OK rendering the blog in my brwoser.

``` bash
$ hexo server
```

I can see the local version of my blog in http://MY_SERVER_IP:4000 (by default it uses that port)

If everithing looks fine to me it's time to bloud the static content and deploy it.

``` bash
$ hexo generate && hexo deploy
```

And that's all! The new post it's been published in my blog!

The Hexo blog is stored in my [GitHub acccount](https://github.com/a-castellano/hexo_blog) and the static webpage that you are wathing is [there](https://github.com/a-castellano/a-castellano.github.io) too.

I'm not explaining how to set up an hexo blog, the [Hexo documentation](https://hexo.io/docs/) is all you need for doing it.