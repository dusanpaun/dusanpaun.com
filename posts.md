---
layout: default
title: Blog
header: Blog
subheader: My latest posts
---

<div class="blog-list">
  {% for post in site.posts %}
    <div class="blog-post-preview">
      {% if post.banner %}
        <img src="{{ post.banner }}" alt="Banner for {{ post.title }}" class="blog-banner" />
      {% endif %}
      <h2>
        <a href="{{ post.url | relative_url }}">{{ post.title | default: post.slug }}</a>
      </h2>
      <span style="color:#888;font-size:0.95em;">
        {{ post.date | date: "%-d %B %Y" }}
      </span>
    </div>
  {% endfor %}
</div>