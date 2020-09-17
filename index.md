---
title: MuseData Homepage
author: Craig Stuart Sapp
keywords: homepage
permalink: /index.html
vim: ts=3 nowrap
summary: 
---

{% include_relative styles-local.html %}
{% include_relative scripts-local.html %}

<table style="margin-top:20px;" class="menu">
<tr>
<td style="min-width:561px; padding-right:50px; vertical-align:bottom;">
	<div id="levels">
		<div id="level1"></div>
		<div id="level2"></div>
		<div id="level3"></div>
		<div id="level4"></div>
		<div id="level5"></div>
	</div>
	<div id="actionbuttons"></div>
</td>
<td style="vertical-align:top;">
	<select style="margin-bottom: 60px;" id="data-type" onchange='selectTypesettingGroup()'>
		<option value="both">manual and automatic typesettings</option>
		<option value="manual">manual typesettings only</option>
		<option value="automatic">automatic typesettings only</option>
	</select>
	<div style="font-size:90%;" id="info"></div>
</td>
</tr>
</table>




