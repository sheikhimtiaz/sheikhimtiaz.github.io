---
layout: page
title: 
subtitle: "You can always edit a bad page. You can’t edit a blank page."
permalink: /blog/
---

<ul class="list-posts">
    {% for post in site.posts %}
        <li class="post-teaser">
            <a class="post-allign" href="{{ post.url | prepend: site.baseurl }}">
                <span class="post-teaser__title">{{ post.title }}</span>
                <span class="post-teaser__date">{{ post.date | date: "%d %B %Y" }}</span>
            </a>
        </li>
    {% endfor %}
</ul>

