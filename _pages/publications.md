---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Recent papers and talks to be added here soon. In the meantime, see my curriculum vitae for a list of publications: [CV](/files/CV_Leopold_Hess.pdf).  
You can also find my papers on my [Academia.edu](https://radboud.academia.edu/LeopoldHess) or [ResearchGate](https://www.researchgate.net/profile/Leopold_Hess) pages. 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
