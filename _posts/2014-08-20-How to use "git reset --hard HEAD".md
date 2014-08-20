---
layout: post
title: How to use "git reset --hard HEAD"
---

I used "git reset --hard HEAD" today, so I leave a note.

## Situation

* some files were edited, and I wanted to delete edited parts and go back to the latest commit.
* I hadn't had "git add" yet.


## Some tips

* "HEAD" means the latest commit. if you edit your file, working tree moves from the latest commit. If you type "git add", index moves from the latest commit.
* check out the link for more detail: http://d.hatena.ne.jp/murank/20110327/1301224770
