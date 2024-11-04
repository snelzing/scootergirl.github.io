---
layout: default
title: Welcome to Shelby's Blog
---

<header>
    <h1>Welcome to Shelby's Blog</h1>
    <nav>
        <ul>
            <li><a href="about.html">About</a></li>
            <li><a href="tech-blog.html">Tech Blog</a></li>
            <li><a href="politics-blog.html">Politics Blog</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

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
