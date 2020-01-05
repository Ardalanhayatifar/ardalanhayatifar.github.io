---
layout: post
title: "Jekyll Clean Theme"
date: 2014-08-22 16:25:06 -0700
comments: false
categories: Highlights

---
<div class="post-categories">
  {% if post %}
    {% assign categories = post.categories %}
  {% else %}
    {% assign categories = page.categories %}
  {% endif %}
  {% for category in categories %}
  Category: {{category}}
  {% unless forloop.last %}&nbsp;{% endunless %}
  {% endfor %}
</div>
<br>

