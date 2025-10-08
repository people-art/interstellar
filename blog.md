---
lang: en
layout: default
title: Blog - Interstella Project
paginate: 5
permalink: /blog/
---

<div class="container">
  <h1 class="text-center mb-5">Interstella Blog</h1>
  <p class="lead text-center mb-5">Updates on Token Cosmos research, AGI emergence, and project milestones – traversing the frontiers of semantic space.</p>

  {% if paginator.posts %}
    {% for post in paginator.posts %}
      <article class="post mb-5">
        <header>
          <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
          <p class="post-meta">{{ post.date | date: "%B %d, %Y" }} by {{ post.author }}</p>
        </header>
        <div class="post-excerpt">
          {{ post.excerpt | strip_html | truncate: 200 }}
          <a href="{{ post.url }}">Read more &rarr;</a>
        </div>
      </article>
    {% endfor %}

    {% if paginator.total_pages > 1 %}
      <div class="pagination text-center">
        {% if paginator.previous_page %}
          <a href="/blog/page{{ paginator.previous_page }}/" class="btn btn-primary mr-2">&larr; Previous</a>
        {% endif %}
        {% for page in (1..paginator.total_pages) %}
          {% if page == paginator.page %}
            <span class="current-page">{{ page }}</span>
          {% else %}
            <a href="/blog/page{{ page }}/" class="page-link">{{ page }}</a>
          {% endif %}
        {% endfor %}
        {% if paginator.next_page %}
          <a href="/blog/page{{ paginator.next_page }}/" class="btn btn-primary ml-2">Next &rarr;</a>
        {% endif %}
      </div>
    {% endif %}
  {% else %}
    <p class="text-center">No posts yet. Check back for updates on our journey through the Token Cosmos!</p>
  {% endif %}
</div>
