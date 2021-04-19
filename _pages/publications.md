---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
You can find my papers on my [Google Scholar profile](https://scholar.google.com/citations?user=6ArALhAAAAAJ&hl=en&oi=ao).

* **Safiabadi Tali S**, Zhou W. Multiresonant plasmonics with spatial mode overlap: overview and outlook. Nanophotonics. 2019 Jul 11;8(7):1199-225. [[Nanophotonics](https://www.degruyter.com/view/journals/nanoph/8/7/article-p1199.xml)]
* 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
