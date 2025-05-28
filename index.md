---
layout: default
title: Home
header: Dušan Paun
subheader: DevOps Engineer
---

## Summary

I'm a DevOps Engineer with skills in database administration, system administration, application development and software testing. I enjoy connecting people with technology solutions that are easy to use, affordable, and sustainable over time. I'm familiar with, and a huge supporter of, the DevOps culture and how to make it work with a large team in a fast paced environment.

## Skills

My skill set includes:

- Docker
- Kubernetes
- Rancher
- Terraform and Terragrunt
- Vagrant
- Elasticsearch, Logstash and Kibana
- Jenkins
- GitLab Pipelines
- Azure DevOps
- Drone CI

I have a working experience with:

- AWS
- Azure
- GCP
- Digital Ocean
- Linode

---

## Latest Blog Posts

<div class="blog-list">
  {% for post in site.posts limit:3 %}
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
<p><a href="{{ '/posts' | relative_url }}">See all blog posts &rarr;</a></p>

---

## Sample GitHub Projects

Here are some of my recent and favorite GitHub projects:

- [dotfiles](https://github.com/duspaun/dotfiles): My personal Linux/macOS configuration files for a productive terminal and editor setup.
- [devops-toolkit](https://github.com/duspaun/devops-toolkit): A curated collection of scripts and tools for automating DevOps workflows.
- [k8s-lab](https://github.com/duspaun/k8s-lab): Kubernetes learning lab with manifests, Helm charts, and deployment examples.
- [infra-as-code-examples](https://github.com/duspaun/infra-as-code-examples): Real-world Infrastructure as Code samples using Terraform, Ansible, and more.