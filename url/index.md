---
title: MuseData file list page
author: Craig Stuart Sapp
keywords: file list
permalink: /url/index.html
summary: 
---

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
pages files which are already typeset will not be affected by these options).


<select id="option-z">
<option value="6">size 6: staff height 0.08" (2mm)</option>
<option value="14">size 14: staff height 0.19" (4.75mm), for small score size for large ensembles</option>
<option value="16">size 16: staff height 0.21" (5.5mm), for small piano size/medium ensembles</option>
<option selected="selected" value="18">size 18: staff height 0.24" (6mm), for large piano size/small ensembles</option>
<option value="21">size 21: staff height 0.28" (7mm), for orchestral parts</option>
</select>


{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}

