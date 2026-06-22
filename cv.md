---
layout: cv
title: Teaching
permalink: teaching/
jsarr:
- js/scripts.js
---

{% assign instructor_courses = site.data.teaching | where: "ta", false %}
{% assign ta_courses = site.data.teaching | where: "ta", true %}

<div class="teaching-listing">

<p>During my time at GSU, I have served as instructor of record for undergraduate courses on applied data science and international trade. My detailed student evaluations are available upon request.</p>

<details class="teaching-section" open>
	<summary class="teaching-subtitle">Instructor of Record</summary>

	{% for teach in instructor_courses %}
	{% include cv/teaching.html teach=teach %}
	{% endfor %}

</details>

<details class="teaching-section">
	<summary class="teaching-subtitle">Teaching Assistantships</summary>

	{% for teach in ta_courses %}
	{% include cv/teaching.html teach=teach %}
	{% endfor %}

</details>

</div>

[cv]: {{ site.url }}/cv.pdf "My CV."

[poloclub]: http://poloclub.gatech.edu "Polo Club of Data Science"
[gt]: http://gatech.edu "Georgia Tech"
[cse]: http://cse.gatech.edu "GT Computational Science and Engineering"
[coc]: http://www.cc.gatech.edu "GT College of Computing"

[fred]: http://fredhohman.com "Fred Hohman"
[polo]: http://www.cc.gatech.edu/~dchau/ "Polo Chau"
[alex]: http://va.gatech.edu/endert/ "Alex Endert"

[jpl]: https://www.jpl.nasa.gov/ "NASA Jet Propulsion Lab"
[hi]: https://www.hi.jpl.nasa.gov/ "Human Interfaces Group at NASA JPL"
[pnnl]: https://www.pnnl.gov/ "Pacific Northwest National Laboratory"
[dsa]: http://www.pnnl.gov/nationalsecurity/technical/capabilities/computing/data_sciences.stm "Data Sciences and Analytics Group at PNNL"
[msr]: https://www.microsoft.com/en-us/research/ "Microsoft Research"
[msr-hci]: https://www.microsoft.com/en-us/research/group/human-computer-interaction/ "HCI@MSR"

[twitter]: https:/www.twitter.com/fredhohman "@fredhohman"
[github]: https:/www.github.com/fredhohman "github.com/fredhohman"
[nstrf]: https://www.nasa.gov/strg/nstrf "NASA Space Technology Research Fellowship"
