---
title: MuseData file list page
author: Craig Stuart Sapp
keywords: file list
permalink: /list/index.html
summary: 
---

{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}

# Musedata file list #

The following spreadsheet (<a target="_blank"
href="http://bit.ly/musedata-menu">http://bit.ly/musedata-menu</a>)
contains a list of all PDFs available on the musedata.org homepage.
Each entry refers to a specific data file on Bitbucket, Github, or
other website that can be converted into a PDF file with <a
target="_blank" href="http://muse2ps.ccarh.org">muse2ps</a>.  See
also <a target="_blank" href="http://bit.ly/musedata-menu-guidelines">The
publishing guidelines</a> for adding works to this website as well
as making the PDF files available as dynamic links for other websites.

<iframe style="width:100%; height:600px;" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTTZN-R0h99A6x2Xc74PA1NuAFLQbUx8Kw_DsKvZPkJ2Hh_-knqQoeS6Yd07Yb2VoWR7LITIRnTAkSt/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=true"></iframe>

<ul>

<li> Columns labeled <b>LEVEL_1</b> through <b>LEVEL_5</b> are organizational
levels for selecting the file in the menu on the musedata homepage.
Typically level 1 will be the composer's name.  Level 2 could be
the work name, or a genre grouping for major groupings of composer's
works.</li>

<li> The <b>SHORTCUT</b> column lists a unique shortcut string (without
spaces) that represents the given file.  This will be the name of
the downloaded PDF files.</li>

<li> The <b>DATA_URL</b> column contains a URL to the data file
which can be converted into a PDF.  <p> Two file types are possible:
(1) files ending in .md2 (or .msd) are "Musedata Stage 2" files,
which are symbolic representations if the music, (2) files ending
in .iff are more direct representations of the graphical music.
Both formats can be converted into PostScript with the muse2ps
program.  </p> </li>

<li> The <b>URL</b> column contains a URL to the CCARH wiki page
(or other website) related to the musical work. </li>

</ul>

The order of the entries in the spreadsheet will be preserved in
the menu selection on the musedata homepage.  Blank lines can be
added to separate works for readability.  Here is what the final
rendering of the list will look like (refresh page after editing
spreadsheet to view updated list):

<br/>
<a name="musesheet"> </a>
<hr noshade>

# Command-line script #

<a target="_blank" href="musesheet.txt">Here is a PERL script</a>
that can be used to work with the spreadsheet from the command line,
including downloading the MuseData PDFs as well as the data used
to generate the PDF files.

Example options:

`musesheet -p pdfs` &rarr; Save PDFs for all entries in a directory called "pdfs".

`musesheet -d data` &rarr; Save source data files for all entries in a directory called "data".

`musesheet -u` &rarr; Display the URL for the TSV text version of the spreadsheet.

`musesheet -r` &rarr; Download the above spreadsheet as TSV text.

<div style="height:200px"></div>

<hr noshade style="margin-top:50px; margin-bottom:50px;">
<h2 style="padding-bottom:50px;"> Flat listing of scores </h2>
<div style="font-size:14pt; line-height:17pt;" id="flat-list"></div>

