---
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Publications
## Peer-Reviewed Articles

* Yao Wen, **Mengying Xie**, and Chong Chen, "Explaining the Wave of Foreign Participation in Chinese Belt and Road Initiative: Evidence from Spatial Analyses,"[in Chinese] ***World Economics and Politics**, No. 2, 2021, pp. 134-154.
  
* Ling Chen, **Mengying Xie**, "How do hard regimes absorb, overlap, and squeeze out soft regimes? Insights from global carbon markets,"[in English] ***Global Public Policy and Governance***, 3:60-85 
