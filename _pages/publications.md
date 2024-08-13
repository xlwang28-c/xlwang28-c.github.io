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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<h2>Working Papers</h2>
[W1] Xiaoge Zhang, <b>Xiao-Lin Wang</b>, Indranil Bose, Fenglei Fan, Yiu-Ming Cheung (2024) Enhancing the Performance of Neural Networks Through Causal Discovery and Integration of Domain Knowledge, <i>European Journal of Operational Research</i>, under 2nd round revision.

[W2] Jianyu Xu, Miao Song, <b>Xiao-Lin Wang</b> (2024) An Online State-Dependent Successive Elimination Algorithm for Rested Bandits, <i>Management Science</i>, under major revision. 

[W3] Peng Liu, Guanjun Wang, <b>Xiao-Lin Wang</b>* (2024) Classical Periodic Replacement Policy Revisited: An Operational Statistics Perspective, <i>IISE Transactions</i>, under major revision.  

[W4] <b>Xiao-Lin Wang</b>, Shizhe Peng*, Xiaoge Zhang, Jianyu Xu (2024) Spare parts provisioning with installed base information: An integrated forecasting and stocking approach, <i>International Journal of Production Research</i>, under review. 

[W5] <b>Xiao-Lin Wang</b>, Shizhe Peng, Xiaoge Zhang* (2024) Price Competition in an Oligopolistic Extended Warranty Market, <i>European Journal of Operational Research</i>, under review.  

[W6] Pingping Dong, <b>Xiao-Lin Wang</b>, Indranil Bose, Kam K. H. Ng, Xiaoning Zhang, Xiaoge Zhang* (2024) Causally-Aware Spatio-Temporal Multi-Graph Convolution Network for Accurate and Reliable Traffic Prediction, <i>INFORMS Journal of Computing</i>, under review.

[W7] Zan Li, Jianyu Xu, Chengjie Wang, <b>Xiao-Lin Wang</b>* (2024) Bayesian Reliability Demonstration Testing via Generalized Test Statistic, <i>European Journal of Operational Research</i>, under review.  
