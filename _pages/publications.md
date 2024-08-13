---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.pubtype == 'papers' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Working Papers</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'manuscripts' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
