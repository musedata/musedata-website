---
title: SUPRA Homepage
author: Craig Stuart Sapp
keywords: homepage
permalink: /parts/index.html
vim: ts=3
summary: 
---

<style>

.menu tr:hover {
	background: #fbfbf9;
}

</style>


# Instrumental parts #

Choose an instrument from the menu below to display available parts in the musedata database:

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
</select>

<div style="margin-top:50px;" id="list"></div>

{% include_relative styles-local.html %}
{% include_relative scripts-local.html %}



