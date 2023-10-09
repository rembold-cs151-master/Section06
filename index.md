---
title: "Section 06: Interactive Graphics"
author: Jed Rembold and Eric Roberts
date: "Week of October 9th"
slideNumber: true
theme: monokai
highlightjs-theme: monokai
width: 1920
height: 1080
transition: fade
css:
  - css/codetrace.css
  - css/roberts.css
  - DrawYinYangLayers.css
tracejs:
  - DrawYinYangLayers
extrajs:
  - js/pgl.js
---


## Problem 1
::::::cols
::::col
- Your first task of the day is to recreate a Yin-Yang symbol, centered in the window, as seen to the right.
- At first glance, this may not look possible given the `GObject`s discussed so far in class, but clever layering of known shapes will get you there!
::::

::::col

<svg ViewBox="0 0 400 400" width=70%>
<rect width="400" height="400" fill="white" />
<circle cx="200" cy="200" r="160" />
<rect x="200" y="40" width="160" height="320" fill="white" />
<circle cx="200" cy="120" r="80" />
<circle cx="200" cy="280" r="80" fill="white" />
<circle cx="200" cy="280" r="20" />
<circle cx="200" cy="120" r="20" fill="white"/>
<circle cx="200" cy="200" r="160" fill="none" stroke-width="3" stroke="black"/>
</svg>

::::
::::::



## Try it! {data-state="DrawYinYangLayersTrace"}
<table style="margin:auto;">
<tbody style="border:none; background-color:#272822;">
<tr style="border:none; background-color:#272822; padding:0px;">
<td colspan=2 style="border:none; background-color:#272822; padding:0px;">
<div id="DrawYinYangCanvas" class="CTCanvas"
     style="border:none; background-color:#272822;"></div>
</td>
</tr>
<tr>
<td style="text-align:center; width:948px;">
<table class="CTControlStrip">
<tbody>
<tr>
<td>
<img id=DrawYinYangResetButton
     style="width:100px;"
     src="images/ResetControl.png"
     alt="ResetButton" />
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>



