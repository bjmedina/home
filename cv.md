---
title: CV
permalink: /cv/
categories: Experience
---

Here's my [cv](https://bjmedina.github.io/images/pdf/bjm_cv.pdf).

**Experiences**

<div class="content list">

  {% for post in site.categories.Experience %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">- {{ post.title }}</a>
      </p>
    </div>
  {% endfor %}

</div>