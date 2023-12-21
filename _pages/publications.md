---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
1.Qingqing Li, Ying Xie, Jinyi Lin, Miaomiao Li, Ziyan Gu, Tianli Xin, Yang Zhang, Qixia Lu, Yihui Guo, Yanhong Xing, Wuyang Wang, “Microglia sing the prelude of neuroinflammation-associated depression”, Molecular Neurobiology.(under review)
2.Qingqing Li, Siyu Fan, Xiaonan Pang, Weijie Xie, “Systemic Lupus Erythematosus Comorbid with Major Depressive Disorder from the Perspective of IL-7R”, Aging. (under review)
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
