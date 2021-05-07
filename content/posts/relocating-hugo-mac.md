---
title: "Relocating Hugo to a new Mac"
date: 2021-05-07T22:22:41+08:00
draft: false
---

I was on Windows 10 and recently moved to a M1 MacBook Air.  Here's how I went about recreating the environment for Hugo on Mac.

My Hugo folder is created in /Documents/Hugo

When in the folder, issue:

``` git
git init
git clone https://github.com/your-depository/your-hugoblog.git
```

If you have setup the submodules for themes and public, then issue:

``` git submodule update --init --recursive ```

This will update the respective folders.

That's all to it!



