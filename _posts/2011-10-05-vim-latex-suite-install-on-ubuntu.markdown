---
author: admin
categories:
- Instructional
comments: true
date: 2011-10-05 14:43:50+00:00
layout: post
slug: vim-latex-suite-install-on-ubuntu
tags:
- Ubuntu
- linux
- latex-suite
- latex
- package management
- install
- vim
title: Vim Latex Suite Install on Ubuntu
---


Ubuntu doesn't manage vim's addons, so installing the `vim-latexsuite` package doesn't actually put all the relevant hooks into your vim installation. To do that, (after installing the package) execute;
`sudo vim-addons -w install latex-suite`
