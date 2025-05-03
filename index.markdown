---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

---
layout: default
title: "Truevalu - Stock Market Insights"
---

<div class="landing-page">
  <section id="hero">
    <h1>Welcome to Truevalu</h1>
    <p>Your source for stock market tips, trends, and analysis.</p>
  </section>

  <section id="articles">
    <h2>Articles</h2>
    <p>Stay up-to-date with the latest stock market insights!</p>
    <ul>
      {% for post in site.posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
      {% endfor %}
    </ul>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Learn more about the founder and the mission behind Truevalu.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Get in touch to discuss stock market insights or collaborations.</p>
  </section>
</div>
