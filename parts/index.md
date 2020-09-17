---
title: Musedata instrumental parts page
author: Craig Stuart Sapp
keywords: insturmental parts
permalink: /parts/index.html
vim: ts=3
summary: 
---

{% include_relative styles-local.html %}
{% include_relative scripts-local.html %}


# Instrumental parts #

Choose an instrument from the following menu to display available
parts in the musedata database:

<select id="instrument" onchange="doSearch();">
	<option value="flute">flute</option>
	<option value="oboe">oboe</option>
	<option value="clarinet">clarinet</option>
	<option value="bassoon">bassoon</option>
	<option value="horn">horn</option>
	<option value="trumpet">trumpet</option>
	<option value="timpani">timpani</option>
	<option value="violin">violin</option>
	<option value="viola">viola</option>
	<option value="violoncello">violoncello</option>
	<option value="contrabass">contrabass</option>
	<option value="continuo">continuo</option>
</select>

<div style="margin-top:50px;" id="list"></div>




