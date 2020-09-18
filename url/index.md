---
title: URL typesetting
author: Craig Stuart Sapp
keywords: URL typeset
permalink: /url/index.html
vim: ts=3 nowrap ft=html
summary: 
---

{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}


# Musedata typesetting by URL #

Type or paste the URL of a Musedata file in the following box,
and then press the red button to typeset the data into a PDF file.

<input id="url" size="50">
<div id="actionbuttons">
	<div class='pdfbutton' 
		onclick='generatePdf("#url")'>
		Generate PDF
	</div>
</div>


<hr noshade>

<h2> Typesetting parameters </h2>

The following parameters control typesetting of Musedata stage 2 files (Music
pages files that are already typeset will not be affected by these options).

<h3> Music size </h3>
<select id="option-z">
<option value="6">size 6: staff height 0.08" (2mm)</option>
<option value="14">size 14: staff height 0.19" (4.75mm), for small score size for large ensembles</option>
<option selected="selected" value="16">size 16: staff height 0.21" (5.5mm), for small piano size/medium ensembles</option>
<option value="18">size 18: staff height 0.24" (6mm), for large piano size/small ensembles</option>
<option value="21">size 21: staff height 0.28" (7mm), for orchestral parts</option>
</select>

<h3> Footer text </h3>

<table width="100%">
<tr>
	<td><input id="L3" placeholder="footer top left"  style="width:500px;"></td>
	<td><input id="R3" placeholder="footer top right" style="width:500px;"></td>
</tr>
<tr>
	<td><input id="L2" placeholder="footer middle left"  style="width:500px;"></td>
	<td><input id="R2" placeholder="footer middle right" style="width:500px;"></td>
</tr>
<tr>
	<td><input id="L1" placeholder="footer bottom left"  style="width:500px;"></td>
	<td><input id="R1" placeholder="footer bottom right" style="width:500px;"></td>
</tr>
</table>

Footer abbreviations: `%P` for page number, `%C` for total count of pages, `%D` for today's
date, `%Y` for today's year; `(C)` for copyright symbol.




