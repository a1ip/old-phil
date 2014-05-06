---
layout: post
title: "Page build failed"
date: 2014-04-30 18:51:27 +0400
comments: true
categories: [ruby, octopress, jekyll, deploying, rake,Github Pages]
---

В какой-то момент у меня возникли проблемы с размещением блога на [Github Pages](https://pages.github.com/):

>The page build failed with the following error:
>
>Page build failed.

Благодарю автора статьи [Adventures in Ruby](http://warewolf.github.io/blog/2013/04/28/adventures-in-ruby/), проблема решилась закомментированием строчки ``require "bundler/setup"`` в файле ``Rakefile``.
