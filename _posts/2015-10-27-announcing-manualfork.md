---
layout: post
section-type: post
title: announcing manualfork - simple restriction-less forking
category: tech
tags: [ 'open source', 'github', 'fork', 'repos', 'mirror', 'clone' ]
---

I'm pleased to announce the release of a brand new service / npm module: 
**[manualfork](http://manualfork.therebelrobot.com)**. 
Designed to work around the forking limitations of Github, manualfork allows you to mirror a repo without 
the need to resort to the command line. Simply log in with your Github account, input your source 
repo and where you want it mirrored to, and you're good to go. 

<img src="https://i.imgur.com/yft41S2.png" style="max-width:100%;" />

## why?

I recently started diving into my work with [Code for San Francisco](http://codeforsanfrancisco.org) and realized 
that not everyone involved with tech knows how to use Github, let alone how to use the command-line. So when 
there are template repos that are targeting these kind of users, they run into the problem of 
[forking restrictions](https://github.com/codeforboston/project-template/issues/7). I knew there was a 
[simple solution](https://help.github.com/articles/duplicating-a-repository/) for this, 
I had done it many times before. I didn't, however, know how to explain this to someone who has 
no knowledge of command-line, let alone git, and who honestly may not have the time/energy to learn. 
Civic Tech Volunteers are donating their time whenever its available, and the easier the steps are 
to get a project started, the better. You can add a manualfork badge to any repo, and streamline 
the process for your developers.

![manual-fork-badge](http://manualfork.therebelrobot.com/img/badge-big.png)

## CLI also available

On top of the heroku-based service linked above, I also 
[released the underlying library](https://github.com/therebelrobot/node-manualfork) with a handy CLI
to make the lives of those of us that traipse into the wild west of the terminal a little less wild.

## Definitely v1

There is definitely room to grow. I need to enable force pushing for when you don't want to create 
a new repo, I also want to add some UI sugar, like prefetching the urls and make sure they are there before
submitting, also want to do some cleanup and standardizing of the codebase, make it a little more sane 
to work with. Any help with these would be spectacular. Feel free to check out the 
[roadmap](https://github.com/therebelrobot/manualfork#roadmap) or
[open a new issue](https://github.com/therebelrobot/manualfork/issues/new) if there is anything missing
that you want to see added!

Cheers!

~*Trent*
