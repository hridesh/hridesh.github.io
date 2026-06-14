---
layout: page
title: News
subtitle: Milestones, awards, papers, and student successes from the lab and the School.
permalink: /news/
---

<p class="callout">For the most up-to-date news, see my <a href="https://www.linkedin.com/in/hrideshrajan/">LinkedIn profile</a>, where I post frequent updates and invite you to follow.</p>

<div class="post-list">
  {% for post in site.posts %}
    <article class="post-card">
      <div class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</div>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <div class="entry">{{ post.excerpt }}</div>
      <a class="read-more" href="{{ site.baseurl }}{{ post.url }}">Read more</a>
    </article>
  {% endfor %}
</div>
