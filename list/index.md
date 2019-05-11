---
title: MuseData file list page
author: Craig Stuart Sapp
keywords: file list
permalink: /list/index.html
summary: 
---


# Musedata menu list #

The following spreadsheet contains a list of all PDFs available on
the musedata homepage.  Each line references a specific file on
Bitbucket that can be converted into a PDF file with muse2ps.  

<iframe style="width:100%; height:600px;" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTTZN-R0h99A6x2Xc74PA1NuAFLQbUx8Kw_DsKvZPkJ2Hh_-knqQoeS6Yd07Yb2VoWR7LITIRnTAkSt/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=true"></iframe>

<ul>

<li> Columns labeled LEVEL_1 through LEVEL_5 are organizational levels for selecting the file
in the menu on the musedata homepage.  Typically level 1 will be the composer's name.  Level 2
could be the work name, or a genre grouping for major groupings of composer's works.</li>

<li> The "SHORTCUT" column lists a unique shortcut string (without spaces) that represents the given
file.</li>

<li> The "DATA_URL" column contains a URL to the data file which can be converted into a PDF. 
<p> Two file types are possible: (1) files ending in .md2 are
"Musedata Stage 2" files, which are symbolic representations if the
music, (2) files ending in .iff are more direct representations of
the graphical music.  Both formats can be converted into PostScript
with the muse2ps program.  </p>
</li>

<li> The "WIKI_URL" column contains a URL to the CCARH wiki page related to the musical work. </li>

</ul>

The order of the entries in the spreadsheet will be preserved in the menu selection on the musedata
homepage.  Blank lines can be added to separate works for readability.




<div style="height:500px"></div>

{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}

