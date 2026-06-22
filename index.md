---
layout: home
title: Home
---

<div id="intro-wrapper" class="l-text">
	<div id="intro-title-wrapper">
		<div id="intro-image-wrapper">
			<img id="intro-image" src="/images/outdoor_headshot.svg"></div>
		<div id="intro-title-text-wrapper">
			<h1 id="intro-title">Cade Lawson</h1>
			<div id="intro-subtitle">Georgia State University</div>
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
		Welcome! I am a Ph.D. candidate in the Department of Economics at Georgia State University <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/gsu.png">. I research topics in <b>public economics</b> related to education policy, food security, and child wellbeing. I am a graduate research assistant in the <a href="https://gpl.gsu.edu/">Georgia Policy Labs</a>. 
	</div>
	<div style="height: 1rem"></div>
	<div>
		In Fall 2026, I will join the Jimmy and Rosalynn Carter School of Public Policy at Georgia Tech <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/gt.png"> as a Postdoctoral Fellow.
	</div>
	<div style="height: 1rem"></div>
	<div>
		My research at GSU is supported by the National Science Foundation's Graduate Research Fellowship. I received my BS in Economics and MS in Data Analytics from Georgia Tech <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/gt.png">. I've also spent time as a research intern at the National Lab of the Rockies <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/nlr.jpg"> and the Federal Reserve Bank of Boston <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/frb.jpeg">. 
  
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
