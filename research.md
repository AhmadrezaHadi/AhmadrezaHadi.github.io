---
layout: page
permalink: /research/
title: Research
---

<!-- Describe your research interests here. -->

<!-- <h2>Publications</h2>
<ul>
	<li>
		<b>"Paper title #1"</b><br>
		<i>List of authors</i><br>
		Conference, Year<br>
		<a href=""><div class="color-button">pdf</div></a><a href=""><div class="color-button">cite</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
	<li>
		<b>"Paper title #1"</b><br>
		<i>List of authors</i><br>
		Conference, Year<br>
		<a href=""><div class="color-button">pdf</div></a><a href=""><div class="color-button">cite</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
</ul> -->

<h2>Research Projects</h2>
<ul>
	{%for r in site.data.research%}
	<li>
		<b>{{r.title}}</b><br>
		{{r.university}}, {{r.year}}<br>
		<i>{{r.description}}</i><br>
		<a href="{{r.url}}" target="_blank"><div class="color-button">code (not complete)</div></a>
	</li><br>
	{%endfor%}
	<!-- <li>
		<b>Project title</b><br>
		University, Duration<br>
		<i>Other details such as advisor's name may go here</i><br>
		<a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br> -->
</ul>

<!-- <h2>Research Implementations</h2>
<ul>
	<li>
		<b>Title #1</b>: Brief description of this research implementation.<br>
		<a href=""><div class="color-button">paper</div></a><a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
	<li>
		<b>Title #2</b>: Brief description of this research implementation.<br>
		<a href=""><div class="color-button">paper</div></a><a href=""><div class="color-button">report</div></a><a href=""><div class="color-button">code</div></a>
	</li><br>
</ul> -->