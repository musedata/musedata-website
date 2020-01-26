---
title: MuseData file list page
author: Craig Stuart Sapp
keywords: file list
permalink: /list/index.html
summary: 
---


# Musedata file list #

The following spreadsheet 
(<a target="_blank" href="http://bit.ly/musedata-menu">http://bit.ly/musedata-menu</a>)
contains a list of all PDFs available on the musedata homepage.
Each line references a specific file on Bitbucket, Github, or other
website that can be converted into a PDF file with muse2ps.

<iframe style="width:100%; height:600px;" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTTZN-R0h99A6x2Xc74PA1NuAFLQbUx8Kw_DsKvZPkJ2Hh_-knqQoeS6Yd07Yb2VoWR7LITIRnTAkSt/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=true"></iframe>

<ul>

<li> Columns labeled LEVEL_1 through LEVEL_5 are organizational
levels for selecting the file in the menu on the musedata homepage.
Typically level 1 will be the composer's name.  Level 2 could be
the work name, or a genre grouping for major groupings of composer's
works.</li>

<li> The "SHORTCUT" column lists a unique shortcut string (without
spaces) that represents the given file.  This will be the name of
the downloaded PDF files.</li>

<li> The "DATA_URL" column contains a URL to the data file which
can be converted into a PDF.  <p> Two file types are possible: (1)
files ending in .md2 are "Musedata Stage 2" files, which are symbolic
representations if the music, (2) files ending in .iff are more
direct representations of the graphical music.  Both formats can
be converted into PostScript with the muse2ps program.  </p> </li>

<li> The "WIKI_URL" column contains a URL to the CCARH wiki page
related to the musical work. </li>

</ul>

The order of the entries in the spreadsheet will be preserved in
the menu selection on the musedata homepage.  Blank lines can be
added to separate works for readability.  Here is what the final
rendering of the list will look like (refresh page after editing
spreadsheet to view updated list):


# Command-line script #

<a target="_blank" href="musesheet.txt">Here is a PERL script</a>
that can be used to work with the spreadsheet from the command line,
including downloading the MuseData PDFs as well as the data used
to generate the PDF files.

<br/>
<hr noshade>

Here is a list of the MuseData works generated from the above spreadsheet:

<br/>
<br/>

<div style="font-size:14pt; line-height:17pt;" id="list"></div>


<div style="height:200px"></div>

{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}

