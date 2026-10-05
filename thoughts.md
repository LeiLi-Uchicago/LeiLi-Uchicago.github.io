---
layout: page
title: Thoughts
subtitle: Notes on scientific AI, computational biology, and research
permalink: /thoughts/
---

<style type="text/css">
.thoughts-intro {
  margin-bottom: 2rem;
  color: #555;
  font-size: 1.05rem;
  line-height: 1.7;
}

.thought-list {
  display: flex;
  flex-direction: column;
  gap: 18px;
  margin-top: 24px;
}

.thought-card {
  padding: 22px 26px;
  border: 1px solid #e7e7e7;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.15s ease, transform 0.15s ease;
}

.thought-card:hover {
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.10);
  transform: translateY(-2px);
}

.thought-title {
  margin: 0 0 6px;
  font-size: 1.4rem;
  font-weight: 700;
  line-height: 1.35;
}

.thought-title a {
  text-decoration: none;
}

.thought-meta {
  font-size: 0.88rem;
  color: #888;
  margin-bottom: 10px;
}

.thought-excerpt {
  color: #444;
  line-height: 1.65;
  margin-bottom: 12px;
}

.thought-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 12px;
}

.thought-tag {
  display: inline-block;
  padding: 3px 9px;
  border-radius: 999px;
  background: #f3f6f9;
  color: #526477;
  font-size: 0.78rem;
}

.thought-links {
  margin-top: 14px;
  font-size: 0.92rem;
}

.thought-links a {
  margin-right: 16px;
}

@media (max-width: 600px) {
  .thought-card {
    padding: 18px;
  }

  .thought-title {
    font-size: 1.25rem;
  }
}
</style>

<div class="thoughts-intro">
I write about scientific AI, computational biology, single-cell and multi-omics research, and the challenges of using increasingly capable AI systems in scientific work. Many of these notes begin as LinkedIn posts and are archived here in a more permanent form.
</div>

{% assign thoughts = site.categories.thoughts %}

{% if thoughts and thoughts.size > 0 %}

<div class="thought-list">

{% for post in thoughts %}

<div class="thought-card">

<div class="thought-title">
<a href="{{ post.url | relative_url }}">{{ post.title }}</a>
</div>

<div class="thought-meta">
{{ post.date | date: "%B %-d, %Y" }}
{% if post.subtitle %}
 · {{ post.subtitle }}
{% endif %}
</div>

<div class="thought-excerpt">
{% if post.description %}
{{ post.description }}
{% elsif post.excerpt %}
{{ post.excerpt | strip_html | truncatewords: 45 }}
{% endif %}
</div>

{% if post.tags %}
<div class="thought-tags">
{% for tag in post.tags %}
<span class="thought-tag">{{ tag }}</span>
{% endfor %}
</div>
{% endif %}

<div class="thought-links">
<a href="{{ post.url | relative_url }}">Read more →</a>

{% if post.linkedin %}
<a href="{{ post.linkedin }}" target="_blank" rel="noopener noreferrer">LinkedIn ↗</a>
{% endif %}
</div>

</div>

{% endfor %}

</div>

{% else %}

<p>No thoughts posted yet.</p>

{% endif %}