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
		<a href="Cade_Lawson_CV.pdf"><div><i class="fa fa-portrait icon icon-right-space"></i>CV</div></a>
		<a href="{{ site.url }}/projectsBREAK"><div><i class="fa fa-shapes icon icon-right-space"></i>Projects</div></a>
		<a href="{{ site.url }}/everything-elseBREAK"><div><i class="fa fa-list-ul icon icon-right-space"></i>Everything Else</div></a>
	</div>
	<div>
		Welcome! I am a Ph.D. student in the Department of Economics at Georgia State University. My research focuses on issues in <b>public economics</b>, especially those related to social mobility, the economics of education, and the social safety net.
	</div>
	<div style="height: 1rem"></div>
	<div>
		I am a graduate research assistant in the <a href="https://gpl.gsu.edu/">Georgia Policy Labs</a>, where I work in the Metro Atlanta Policy Lab for Education. My research at GSU is supported by the National Science Foundation's Graduate Research Fellowship.  
		
	</div>
	<div style="height: 1rem"></div>
	<div>
		I received my BS in Economics and my MS in Data Analytics from Georgia Tech <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/gt.png">, where I was a research assistant in the <a href="https://datasciencepolicy.gatech.edu/">Data Science and Policy Lab</a> for 4 years. I've previously spent time as a research intern at the National Renewable Energy Lab <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/nrel.png"> and the Federal Reserve Bank of Boston <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/frb.png">. 
  
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
