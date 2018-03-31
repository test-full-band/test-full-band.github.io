---
title: Quants2D - quantization grid pattern
keywords: quantization, banding, posterization
tags: [getting_started]
sidebar: vtest_sidebar
permalink: vtest_Quants2D.html
folder: vtest
---

Samples of good and bad rendering of Quants2D set of test patterns (for the sake
of clarity when displaying on web page we amplify here intensity of the pattern
4 times, it is supposed to be watched in dark room on the tv screen and will be
dim compared to pictures bellow).

## The reference

8 bit YUV to 10 bit RGB:
![10bit](images/vtest/Quants.png)

8 bit YUV to 8 bit RGB dithered:
![8bit](images/vtest/Quants8tpdf.png)

## Not so good to epic fail examples

8 bit YUV to 8 bit RGB truncated (satisfying):
![8bit](images/vtest/Quants8bit.png)

8 bit YUV to 7 bit RGB truncated (bad):
![7bit](images/vtest/Quants7bit.png)

8 bit YUV to 6 bit RGB truncated (worse):
![6bit](images/vtest/Quants6bit.png)

8 bit YUV to 5 bit RGB truncated (terrible):
![5bit](images/vtest/Quants5bit.png)

{% include links.html %}
