---
layout: tag
title: Tags
permalink: tag
---

<section class="py-6 text-base-content">
  <div class="max-w-3xl mx-auto">
    <h1 class="text-3xl font-bold mb-8 text-center text-base-content">Tags</h1>
    <div class="space-y-8">
      {% for tag in site.tags %}
        <div class="card bg-base-100/20 backdrop-blur-sm shadow-xl">
          <div class="card-body">
            <h3 id="{{ tag[0] }}" class="card-title text-base-content">{{ tag[0] }}</h3>
            <ul class="space-y-2">
              {% for post in tag[1] %}
                <li class="flex items-center">
                  <div class="badge badge-primary badge-outline mr-2">{{ tag[0] }}</div>
                  <a href="{{site.baseurl}}{{ post.url }}" class="text-base-content hover:text-primary">{{ post.title }}</a>
                </li>
              {% endfor %}
            </ul>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</section>


