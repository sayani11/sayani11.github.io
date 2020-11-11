---
layout: about
title: about
permalink: /
description: Junior Reseach Fellow | Dept of Bioinformatics, BHU.
order: 1

profile:
  align: right
  image: prof_pic.jpg
  address: ""
news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
years: [1956, 1950, 1935]
---

I am Sayantoni. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.  

**Reseach Interests**: I am interested in reseach too, stuff like things and all. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.  

**Contact**: say [dot] sayani [at] gmail [dot] com

---

<div class="post">
{% include news.html %}
</div>

---

{: #publications}

## __Publications__


<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

---

