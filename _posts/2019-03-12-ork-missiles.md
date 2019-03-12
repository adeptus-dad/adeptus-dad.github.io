---
layout: post
title:  "Parametric Ork Missiles in OpenScad"
date:   2019-03-12 00:00:00
author: Dad
tags:   [28mm, openScad, ork]
feature-img: "assets/img/ork/missiles-banner.png"
comments: true
---

![missiles][missiles]
My [recent order][proteus] to Shapeways was the occasion to try something I whipped up a while ago: parametric ork missiles! For a long time, I've wanted to convert stantard shooty boyz to tankbustas simply by adding a missile to the front of their shoota. The reasoning being that firing a bullet in a missile was a very good way to launch it.

I was just needing some propa' orky missiles, so I went to OpenScad. And of course, the beauty of OpenScad is that your 3D models can be *parametric*. So, if you have a parametric missile model and some random values, you can generate any number of different missiles. The parameters I choose were:
- radius of the missile
- length of the warhead
- length of the body
- size of the fins
- number of fins

Main OpenScad code below. Feel free to reuse/modify it! I'll post the result as I receive my order from Shapeways.

<script src="https://gist.github.com/adeptus-dad/dfbb9b4c33fbc11f804af11db851f412.js"></script>


[missiles]: {{ site.baseurl }}/assets/img/ork/missiles.png
[proteus]: {{ site.baseurl }}/2019/03/08/warhound-proteus-2.html


