---
title: 'I finally understand RAID redundancy'
source: http://www.larryjordan.biz/raids-and-performance/
tags: tech
layout: link
---

What’s puzzled me the longest has been RAID 5. How can one drive allow for data redundancy on a five drive array? [Now I get it][1].

> This works because all digital data is stored as either a 1 or a 0. Imagine a 3D checkerboard—let's make it 5 stories high. Look down on the top left square and count the number of checkers on that square for each of the top four layers. If they total an odd number, put a checker on the same square on the bottom layer. If they total an even number, don't put a checker on the same square on the bottom layer.

[1]:http://www.larryjordan.biz/raids-and-performance/