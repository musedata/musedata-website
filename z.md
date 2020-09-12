---
title: Spreadsheet TSV test
author: Craig Stuart Sapp
keywords: testpage
permalink: /z.html
vim: ts=3
summary: 
---

<script>

document.addEventListener("DOMContentLoaded", function() {
	var id = "AKfycbzffB12IgUoGzJlIXvrV-9OLEk-OEBrUrAi0D1OmQkfsV7XWMU";
	var url = "https://script.google.com/macros/s/" + id + "/exec";
	var url2 = "https://script.google.com/d/1d59rM3iG6FIQSOlTeELU6nTpgi96c042_R-BpC7kuyIhP3rDc57xNbck/edit?usp=sharing";
 	var request = new XMLHttpRequest();
	request.open("GET", url2);
	request.send();
	request.addEventListener("load", function() {
		var data = request.responseText;
		var delement = document.querySelector("#data");
		delement.innerHTML = data;
	});
});

</script>

<pre id="data">DATA WILL BE PLACED HERE</pre>

