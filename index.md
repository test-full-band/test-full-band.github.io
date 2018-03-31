---
title: "Welcome to the testing-video project!"
keywords: sample homepage
tags: [getting_started]
sidebar: vtest_sidebar
permalink: index.html
---

You can download latest set of patterns from [releases](https://github.com/testing-av/testing-video/releases) page.

## Features (current [release 0.0.3](https://github.com/testing-av/testing-video/releases/download/0.0.3-preview/testing-video-0.0.3-SNAPSHOT-lossless.zip))

* HDR10 5%, 10%, 20%, 50% window calibration patterns in 5% steps
* HDR10 10% window calibration patterns for LG OLED 2016 and 2017
* HDR10 2D quantization steps test patterns
* HDR10 log sine sweep concentric circles patterns for luma and chroma (beta)

All patterns are automatically validated after encoding by decoding them and comparing with reference.

## In Development for the next release

Just a small announce of what already can be built from sources on our GitHub
[project](https://github.com/testing-av/testing-video) page.

Modern picture formats:
  * H.264 (AVC) and H.265 (HEVC)
  * FullHD (1080p) and UltraHD 4K (2160p)
  * BT.709 and BT.2020 color
  * 4:2:0 YCbCr and ICtCp
  * Standard dynamic range and HDR (HDR10, HLG10)

Tests:
  * BT.2111 color bar test pattern for HDR10 and HLG10
  * Quantization uniformity / local non-linearity detection:
    * 2D Quantization grid
    * 3D Quantization cross pattern (dynamic sweep)

{% include links.html %}
