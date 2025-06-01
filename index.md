---
layout: default
title: Home
header: Hi, I'm Dušan.
subheader: Exploring the world of Observability and DevOps.
---

I'm a DevOps Engineer with skills in database administration, system administration, application development and software testing. I enjoy connecting people with technology solutions that are easy to use, affordable, and sustainable over time. I'm familiar with, and a huge supporter of, the DevOps culture and how to make it work with a large team in a fast paced environment.

## Latest Blog Posts

<div class="blog-list">
  {% for post in site.posts limit:5 %}
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
  <div class="blog-post-preview" style="display: flex; align-items: center; justify-content: center;">
    <a href="{{ '/posts' | relative_url }}" style="font-weight: bold; font-size: 1.1rem; color: var(--accent); text-align: center; width: 100%;">
      See all blog posts &rarr;
    </a>
  </div>
</div>

---

## About Me

<p>
  As a DevOps Engineer, I enjoy connecting people with technology solutions that are easy to use, affordable, and sustainable. I have experience in database administration, system administration, application development, and software testing, and I'm a strong advocate for DevOps culture.
  <a href="{{ '/about' | relative_url }}">Learn more about me &rarr;</a>
</p>

---

## Sample GitHub Projects

<p>
  Here are a few of my recent and favorite GitHub projects. You can see more on my GitHub profile.
</p>
<ul>
  <li><a href="https://github.com/dusanpaun/dotfiles" target="_blank" rel="noopener">dotfiles</a>: My personal Linux/macOS configuration files.</li>
  <li><a href="https://github.com/dusanpaun/devops-toolkit" target="_blank" rel="noopener">devops-toolkit</a>: A collection of DevOps automation tools.</li>
  <li><a href="https://github.com/dusanpaun/k8s-lab" target="_blank" rel="noopener">k8s-lab</a>: Kubernetes learning and examples.</li>
</ul>
<p><a href="https://github.com/dusanpaun" target="_blank" rel="noopener">View all my GitHub projects &rarr;</a></p>