---
title: Black Level Setup (PLUGE)
keywords: calibration, black, pluge
tags: [getting_started]
sidebar: vtest_sidebar
permalink: vtest_BlackPLUGE.html
folder: vtest
---

This pattern is for setting black level.
At the middle part of the screen there are bars for (from left to right) -4%, 0, -2%, 0, +2%, 0, +4% gray levels.

At the left side of the screen there is fine-grained pattern for the above black.
It consists of a sequence of (from top to bottom) +2, 0, +1, 0, +3 code points for 8 bit patterns and +4, 0, +2, 0, +6 code points for 10 bit patterns (so in this case it shows three levels below 1% pattern).

At the right side yet again - alternating black and blacker than black levels.

## The reference

If the black level is set correctly you should see two vertical gray bars at the right half of the screen.

In addition to that at the left edge of the screen you might see up to three boxes if the black level is ideally adjusted.
But if some of them become invisible it is still not that bad as long as you still see two bars at right half of the screen.

##### Perfect black level
![10bit](images/vtest/BlackPLUGE.png)

The above is the perfect example of black level adjustment.

Let's see then examples of misadjustment.

##### Too dark
![10bit](images/vtest/BlackPLUGEdark.png)

If you see something like the above is too dark and you need to increase brightness.

##### Too bright
![10bit](images/vtest/BlackPLUGEbright.png)

If you see something like the above is too bright and you need to reduce brightness.

{% include links.html %}
