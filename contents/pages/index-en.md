---
layout: default
title: IXOlist Mass Media
permalink: /
lang: en
page_id: home
---
<div class="news-block">
  {% for new in site.posts %}
    {% if new.lang == page.lang %}
      {% include new-card.html new=new %}
    {% endif %}
  {% endfor %}
</div>


