---
layout: page
permalink: /projects/
title: Projects
---

Here is a non-exhaustive list of my non-research projects. My research work can be found <a href="/research">here</a>. You can also check out my Github profile <a href="">here</a> for a complete list of my projects.

<ul>
	{%for project in site.data.projects%}
	<li>
		<b>{{project.title}}</b>: {{project.description}}<br>
		<a href="{{project.url}}" target="_blank"><div class="color-button">code</div></a>
	</li><br>
	{%endfor%}
</ul>
