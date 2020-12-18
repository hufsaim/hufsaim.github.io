---
layout: single
author_profile: true
---


<div class="grid__wrapper">
{% for post in site.news limit:4 %}
  {% unless post.hidden %}
    {% include archive-single.html type="grid" %}
  {% endunless %}
{% endfor %}
</div>
<br>


[Research](https://sites.google.com/view/yhnam/research)
- ML Applications for Medical Imaging
- Quantitative Medical Imaging
- Advanced MR Neuroimaging Techniques

[Publication](https://scholar.google.co.kr/citations?hl=ko&user=UZcwGAoAAAAJ&view_op=list_works&sortby=pubdate)


<br>

