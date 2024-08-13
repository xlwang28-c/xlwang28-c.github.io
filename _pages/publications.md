---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}


<h2>Journal Papers</h2>
{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}

{% if post.pubtype == 'papers' %}
      {% include archive-single.html %}
      {% else %}
      <h2>Working Papers</h2>
      {% include archive-single.html %}
  {% endif %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}

{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
