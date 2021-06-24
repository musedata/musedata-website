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
	<option value="flute">Flute</option>
	<option value="oboe">Oboe</option>
	<option value="clarinet">Clarinet</option>
	<option value="bassoon">Bassoon</option>
	<option value="horn">Horn</option>
	<option value="trumpet">Trumpet</option>
	<option value="timpani">Timpani</option>
	<option value="violin">Violin</option>
	<option value="viola">Viola</option>
	<option value="violoncello">Violoncello</option>
	<option value="contrabass">Contrabass</option>
	<option value="continuo">Continuo</option>
	<option value="cembalo">Cembalo</option>
</select>

<div style="margin-top:50px;" id="list"></div>




