---
layout: page
title: Blog
permalink: blog
---

<section class="py-6 text-base-content">
  <div class="max-w-3xl mx-auto">
    <h1 class="text-3xl font-bold mb-8 text-center text-base-content">Blog Posts</h1>
    <div class="space-y-6">
      {% for post in site.posts %}
        <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
          <div class="card-body">
            <h3 class="card-title text-base-content">
              <a href="{{ post.url | relative_url }}" class="hover:text-primary">{{ post.title}}</a>
            </h3>
            <div class="text-sm text-base-content opacity-70">{{post.date | date: "%B %-d, %Y"}}</div>
            {% if post.excerpt %}
              <p class="mt-2 text-base-content">{{ post.excerpt }}</p>
            {% endif %}
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</section>


