---
layout: home
title: Home
---

<div id="intro-wrapper" class="l-text">
	<div id="intro-title-wrapper">
		<div id="intro-image-wrapper">
			<img id="intro-image" src="/images/headshot2026_1.jpg"></div>
		<div id="intro-title-text-wrapper">
			<h1 id="intro-title">Cade Lawson</h1>
			<div id="intro-subtitle">Georgia Institute of Technology</div>
			<div id="intro-title-socials">
				{% for link in site.data.social-links %}
					{% if link.on-homepage == true %}
						{% include social-link.html link=link %}
					{% endif %}
				{% endfor %}
			</div>
		</div>
	</div>
	<!-- <hr class="l-middle home-hr"> -->
	<div id="everything-else" class="l-middle">
		<a href="{{ site.url }}/research"><div><i class="fa fa-flask icon icon-right-space"></i>Research</div></a>
		<a href="{{ site.url }}/teaching"><div><i class="fa fa-shapes icon icon-right-space"></i>Teaching</div></a>
		<a href="{{ site.url }}/cv"><div><i class="fa fa-portrait icon icon-right-space"></i>CV</div></a>
	</div>
	<div>
		 Welcome! I am a Postdoctoral Fellow in the Jimmy and Rosalynn Carter School of Public Policy at <b>Georgia Tech</b> <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/gt.png"> and a Research Affiliate with the <a href="https://gpl.gsu.edu/">Georgia Policy Labs</a>.  
	</div>
	<div style="height: 1rem"></div>
	<div>
		 I am an applied microeconomist with research interests at the intersection of <b>public economics</b> and <b>health economics</b>. I study topics related to education policy, food security, and child wellbeing.  
	</div>
	<div style="height: 1rem"></div>
	<div>
		I received my PhD in Economics from the Andrew Young School of Policy Studies at <b>Georgia State University</b> <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/gsu.png">, where my research was supported by the National Science Foundation's Graduate Research Fellowship.
	</div>
</div>


[gt]: http://www.gatech.edu "Georgia Tech"
[cse]: http://cse.gatech.edu "Georgia Tech Computational Science and Engineering"
[coc]: http://www.cc.gatech.edu "Georgia Tech College of Computing"

[cv]: {{ site.url }}/cv
[polo]: http://www.cc.gatech.edu/~dchau/ "Polo Chau"
[alex]: http://va.gatech.edu/endert/ "Alex Endert"
[poloclub]: http://poloclub.gatech.edu "Polo Club of Data Science"
[nstrf]: https://www.nasa.gov/strg/nstrf "NASA Space Technology Research Fellowship"
