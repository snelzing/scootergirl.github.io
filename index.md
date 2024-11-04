---
layout: default
title: Welcome to Shelby's Blog
---

<section id="about">
    <h2>About Me</h2>
    <p>Welcome to my blog! Here, I'll share insights and thoughts on technology, embedded systems, Linux, and more.</p>
</section>

<section id="latest-posts">
    <h2>Latest Posts</h2>
    <ul>
        {% for post in site.posts %}
            <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
        {% endfor %}
    </ul>
</section>

<footer>
    <p>&copy; 2024 Shelby's Blog</p>
</footer>
