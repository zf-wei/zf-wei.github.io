---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

## Research Interest
I am interested in Probability Theory and Graph Theory.

# Preprints & Publications
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Invited Presentations
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
