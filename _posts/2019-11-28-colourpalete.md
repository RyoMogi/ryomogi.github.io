---
layout: post
title:  The print-friendly (grey scale) categorical colour palette
date: 2019-11-28 09:26:00
description: this is what included images could look like
tags: R, rstats
categories: R
---

I have been looking for a colour palette that looks great both in a colour version and a printed version. More and more journals accept articles to have figures with colours, but some of them still do not.

I used to use the palette from this [website](http://dr-k-lo.blogspot.com/2013/07/a-color-blind-friendly-palette-for-r.html): a colour-blind and print-friendly. It worked very well when I used it for three colours. But I realised that more than five colours from this palette do not work so well in a grey scale. So, I started creating a palette myself and after spending "some" hours, I finally got a satisfied my version of the colour palette.

<div class="row mt-3">
    <div class="center">
        {% include figure.html path="assets/img/colourpalette.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In colour
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/colourpaletteBW.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In grey (printed)
</div>

HEX format: `#08306B`, `#238B45`, `#FD8D3C`, `#D4B9DA`, `#FFEDA0`

Please feel free to use it if you like!

I got this idea from Vladimir Canudas-Romo and also received several suggestions from my friends, Ilya ([@ikashnitsky](https://twitter.com/ikashnitsky?s=20&t=YnCNCmVPKK48IGjQG43cmA)) and Tim([@timriffe1](https://twitter.com/timriffe1?s=20&t=YnCNCmVPKK48IGjQG43cmA)). Thanks!!
