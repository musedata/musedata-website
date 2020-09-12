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
	var url2 = "https://script.googleusercontent.com/macros/echo?user_content_key=WB75iAh-g32wZnolt1NfsOMCTMirFTPpptCOKxdSPL1KHzcFvH7UJkGvSNANyyHfQCx6F1kI8Y-YnCLb9fngacL7ARaiOQcam5_BxDlH2jW0nuo2oDemN9CCS2h10ox_1xSncGQajx_ryfhECjZEnPrbGNW7e_0AwJpAcx7b7OKCO9d2f6mbYcHSFC69YlLUERy_1Vvx8tmEZWU5C-oY6g&lib=MYioJghBvS-FIfpuZqIKAOMpfpWsEjBJ5";
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

