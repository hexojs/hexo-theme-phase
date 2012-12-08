---
layout: post
title: FAQ
date: 2011-03-18 10:56:36
comments: true
tags:
- dolor
---

### What's different between Octopress version and Hexo version?

- Octopress version doesn't have `photo` and `link` layout.
- Some little difference.
- <del>Octopress is slower than Hexo.</del>

### How to edit menu?

- Octopress: Edit `source/_includes/custom/navigation.html`.
- Hexo: Edit `menu` parameter in `_config.yml`.

### How to disable Fancybox?

Running Phase Beam and Fancybox at same time may be difficult to Chrome, so you can choice to disable it.

- Octopress: Delete `source/_includes/after_footer.html` in line 1.
- Hexo: Edit `fancybox` parameter to `false` in `_config.yml`.

### How to disable Phase Beam?

I think it is really meaningless to disable Phase Beam when using Phase. Phase without Phase Beam is just Slash with black background, nothing special and less feature than Slash.

- Octopress: Delete `source/_includes/after_footer.html` in line 2.
- Hexo: Delete the last line of `layout/_partial/after_footer.ejs`.

If you have any questions, send me an [issue](https://github.com/tommy351/hexo-theme-phase/issues).