---
layout: post
title: "Bugs in My Code"
date: 2011-10-09 05:40
comments: true
categories: 
- Programming
- Javascript
- Artificial Intelligence
---
This is a little something I've been working on. It's a simulation of ants
looking for food.

<!--more-->

<div id='antsMain'></div>
<ul style="position: relative; list-style: none">
<li style="position: absolute; height: 18px; width: 18px; background: url('/writes/images/trail-label.png') 0 0"></li>
<li style="position: absolute; left: 19px"><input id="showTracksCb" type="checkbox"></li>
<li style="position: absolute; left: 36px; height: 18px; width: 18px; background: url('/writes/images/heart-label.png') 0 0"></li>
<li style="position: absolute; left: 55px"><input id="showHeartsCb" type="checkbox"></li>
</ul>
<script src="/javascripts/ants.js"></script>
<script>
new brigh.ants.AntsLoop(500, 500, {
    parentDivId: 'antsMain',
    showTracksId: 'showTracksCb',
    showHeartsId: 'showHeartsCb'
}).startLooping();
</script>