---
layout: post
title: My First post
date: 2026-05-05 06:10:00 +0900
categories: Code
---
After hours of work, I finally managed to run github blog successfully.
As for the horourable first post, I'll summarize the git commands I learned during the setup.

*GIT* is the version manager for various projects. I can update the project, 'branch out' from the previous version and set back-up points, etc. This makes the project more stable(in a sense that I can undo my mistakes), more systematic. *Github* is a online-version of git, providing remote storage and cooperation chances with other people. There are many additional features in github, which I don't know fully yet. ~~I don't know about git either~~

## 1. First installation and initializing
Having installed [git](https://git-scm.com/) for the first time, you can use git bash as CLI to control git.

{% highlight bash %}
git --version
{% endhighlight %}
This command outputs the current version of git.

{% highlight bash %}
git config --global user.name "Eunsoo Jeon"
git config --global user.email "jsilverwater007@gmail.com"
{% endhighlight %}
Git records the contributer's name and email while commiting(making new version). One can set that with this command.

## 2. Branch, commit
{% highlight bash %}
git branch 
{% endhighlight %}