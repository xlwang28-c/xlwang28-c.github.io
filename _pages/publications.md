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

{% for post in site.publications_papers reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Working Papers</h2>
{% include base_path %}

{% for post in site.publications_manuscripts reversed %}
  {% include archive-single.html %}
{% endfor %}

