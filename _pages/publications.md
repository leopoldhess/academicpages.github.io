---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

A more exhaustive list of papers and talks to be added here soon. In the meantime, see my curriculum vitae for a list of publications: [CV](/files/CV_Leopold_Hess.pdf).  
You can also find my papers on my [Academia.edu](https://radboud.academia.edu/LeopoldHess) or [ResearchGate](https://www.researchgate.net/profile/Leopold_Hess) pages. 

# Recent publications #

{% for post in site.publications reversed %}
 {% include archive-single.html %}
{% endfor %}
