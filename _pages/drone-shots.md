---
layout: archive
title: "Aerial Photography"
permalink: /drone-shots/
author_profile: true
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

## I love to travel with my DJI Mavic Pro, here are some aerial images I have taken.

<head>
<style>
div#container
{
    width:800px;
    height:800px;
    overflow:hidden;     /* if you don't want a scrollbar, set to hidden */
    overflow-x:hidden;   /* hides horizontal scrollbar on newer browsers */

    /* resize and min-height are optional, allows user to resize viewable area */
    -webkit-resize:vertical; 
    -moz-resize:vertical;
    resize:vertical;
    min-height:317px;
}

iframe#embed
{
    width:800px;       /* set this to approximate width of entire page you're embedding */
    height:800px;      /* determines where the bottom of the page cuts off */
    margin-left:-400px; /* clipping left side of page */
    margin-top:-400px;  /* clipping top of page */
    overflow:hidden;

    /* resize seems to inherit in at least Firefox */
    -webkit-resize:none;
    -moz-resize:none;
    resize:none;
}
</style>
</head>

<div id="container">
  <iframe src="https://www.skypixel.com/photo360s/e4cb5e90-1e36-4dae-a902-9bf22fb9e337" allowfullscreen></iframe>
</div>
