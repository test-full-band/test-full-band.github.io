---
title: Calibration patterns
keywords: calibration, grayscale, saturation
tags: [getting_started]
sidebar: vtest_sidebar
permalink: vtest_Calibrate.html
folder: vtest
---

We have plenty of patterns which will help you to calibrate your TV set:

  * Full screen fills and 5%, 10%, 20%, 50% window calibration patches
  * Grayscale patterns in 5% steps
    * additional 'Whiter than White' patterns
    * additional precision near-black patterns (1% steps)
  * Miscellaneous 10 step Saturation Sweep patterns (CalMAN compatible)

All those patterns have small intro displayed first 5 seconds at the top and bottom edges of the screen.
There you can visually identify the pattern and find out useful information you might want to know abotu the pattern.
On the top right site there is usually information about the set this pattern belong to.
Top center display the sequence number and/or the name of the pattern within the set.
Bottom right is for the resolution.

Bottom center is where things get more interesting.
There you can find precise YUV values that are coded into the pattern (as we are coding 4:2:0 there are no RGB values in files).
YUV in this case is not a specific color space, but we are using it as a generalization for color-difference kind of spaces such as Y'C'bC'r and others (we just wanted a unique letter per component).
As those color space coding will not generally decode to integer values of R, G and B we are displaying also RGB values with higher precision (those RGB values shouldn't be rounded by a perfect display system, so the YUV codes solely define of what you or the meter should see on the display).

And finally on the left top and bottom parts you will find color and light levels.
At the top it is displayed according to OETF (Opto-electronic transfer characteristics before non-linear pre-correction).
This means 'camera' light 'as captured'.
Rec. BT.709 and Rec. BT.2020 transfer functions are those 'camera' or encoding transfer functions.
But it is not supposed for the display to use the direct inverse of these functions.
Instead Rec. BT.1888 EOTF (electro-optical transfer function) is recommended for the display.
So we display also how it should be on the display at the bottom. For encodes that are using display EOTF instead as a transfer function (such as HDR10 / SMPTE ST.2084 PQ) only value at bottom of the screen is displayed.


## The reference

##### ColorChecker "C2 - moderate red" 10% window patch example
![Calibrate](images/vtest/Calibrate.png)

{% include links.html %}
