---
layout: post
section-type: post
title: a simple method to multi-fork a Github repo
category: tech
tags: [ 'open source', 'github', 'fork', 'repos', 'lifehack' ]
---

If you've used Github frequently, you may have run across a little issue when it comes to forking. Say, for example, you are looking at a template repo you really like, and would like to build separate repos based off the original. Problem is, after you fork the repo for the first time, the Github UI doesn't allow you to fork it again, it merely routes you to your original fork. This can cause issues, sometimes. What if, for example, you want to copy an existing repo in the same account? Nope. What about if you want to make a completely iterative work off the upstream, and not have it linked anymore? Nogo.

There are [ways around this](https://adrianshort.org/create-multiple-forks-of-a-github-repo/), but if you're not familiar with command line that could be a difficult proposition. I'm in the process of making a tool to make this easier, but in the meantime, you still need to figure out a way to do it.

While Github does restrict the number of times you fork into a specific account, it does *not* restrict the number of organization accounts you can make. Want another fork? Make a new org, name it your-username-2 or whatever, and fork into that. It's hacky, admittedly, and doesn't scale very well, but the option is there.

I'll be posting in the coming days about a new tool I'm working on to prevent the need for command line or account hacks. Stay tuned!

*~Trent*
