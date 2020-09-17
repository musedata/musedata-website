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
	var data = document.querySelector("#data").textContent;
	console.log("DATA TO SEND", data);
	var url = "https://script.google.com/macros/s/AKfycbwPSnUPffm_A_voZXkYy0sks9sWLr9-ig_m2UOPes9DP1Sod3A/exec";
	var request = new XMLHttpRequest;
	var formdata = new FormData();
	formdata.append("humdrum", data);
	request.open("POST", url);
	request.send(formdata);
	request.addEventListener("readystatechange", function (event) {
		console.log("ONREADYSTATECHANGE", event);
		if (request.readyState == XMLHttpRequest.DONE) {
			console.log("DONE WITH POST");
		} else {
			console.log("READYSTATE: ", request.readyState);
		}
	});
});

</script>


<script id="data" type="application/x-humdrum">**kern	**kern
*clefG2	*clefG2
1c	1c
!!LO:LB:g=z
=1	=1
1d;	2g
!	!XXX
!	!LO:N:vis=1
.	2g;
=1	=1
!!!filter: ABC
!!!Xfilter: YSE
*-	*-
!!GLOBAL comment
!!!ONB:	TITLE
</script>



