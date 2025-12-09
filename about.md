---
layout: default
title: Notes
---

<section class="notes-intro">
  <h1>Notes & Reflections</h1>
  <p class="lead">Thoughts on systems, architecture, and the craft of building software that lasts.</p>
</section>

<section class="notes-content">
  <p><em>This space is reserved for deeper explorations into distributed systems, architectural patterns, and lessons learned from building at scale. Check back soon for essays and technical deep-dives.</em></p>
  
  <h2>Recent Posts</h2>
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</section>

<section class="contact-section">
  <h2>Get in Touch</h2>
  <p>If you'd like to discuss systems architecture, share ideas, or collaborate on interesting problems:</p>
  <ul class="contact-list">
    <li>Email: <a href="mailto:mail@ashiskar.me">mail@ashiskar.me</a></li>
    <li>GitHub: <a href="https://github.com/ashiskar" target="_blank" rel="noopener noreferrer">@ashiskar</a></li>
    <li>LinkedIn: <a href="https://www.linkedin.com/in/ashiskar025/" target="_blank" rel="noopener noreferrer">ashiskar025</a></li>
  </ul>
</section>
