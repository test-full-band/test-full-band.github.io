---
title: "Welcome to the testing-video project!"
keywords: homepage
tags: [getting_started]
sidebar: vtest_sidebar
permalink: index.html
---

You can download latest set of patterns from [releases](https://github.com/testing-av/testing-video/releases) page.

## Features

##### Modern picture formats

  * H.264 (AVC) and H.265 (HEVC)
  * FullHD (1080p) and UltraHD 4K (2160p)
  * BT.709 and BT.2020 color
  * 4:2:0 YCbCr
  * Standard dynamic range and HDR (HDR10, HLG10)

##### Setup & Tests

  * PLUGE pattern for precisely setting black level
  * BT.2111 color bar test pattern for HDR10 and HLG10
  * Quantization uniformity / local non-linearity detection:
    * 2D Quantization grid
    * 3D Quantization cross pattern (dynamic sweeps)

##### Calibration patterns

  * Full screen fills and 5%, 10%, 20%, 50% window calibration patches
  * Grayscale patterns in 5% steps
    * additional 'Whiter than White' patterns
    * additional precision near-black patterns (1% steps)
  * Miscellaneous 10 step Saturation Sweep patterns (CalMAN compatible)

##### Special for LG OLED

  * HDR10 10% window calibration patterns for LG OLED 2016 and 2017

All patterns are automatically validated after encoding by decoding them and comparing with reference.

## Expected in following release(s)

  * ICtCp test patterns
  * Injecting ST.2094-10 metadata allowing to test Dolby Vision systems
  * Suggest your wishes via [feature request](https://github.com/testing-av/testing-video/issues) or even better contribute to our GitHub project via pull requests.

{% include links.html %}
