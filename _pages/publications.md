---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

# <u>Research Interest<u>
Random Walk on Graphs, Spectral Graph Theory, Network Science.

***

# <u>Publications<u>
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

***
# <u>Invited Talks</u>
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
