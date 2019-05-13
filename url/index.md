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
		Generate Music PDF
	</div>
</div>

{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}

