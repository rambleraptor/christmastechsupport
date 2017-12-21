---
layout: home
title: Home
---
<div markdown="1" class="container content">
> **The stockings have been stuffed <br />**
> **the morning is near <br />**
> **suddenly something washes over you <br />**
> **uncertainty, fear. <br />**
> **You've got these new smart devices, consoles, and more. <br />**
> **Pray setting up these new smart devices won't be a chore. <br />**
> **Dangers of security, but you can relax, <br />**
> **I'll make sure you make it through the morning, I've got your backs. <br />**

Alright, that's enough rhyming. Anyways, Christmas morning has just rolled around, and there's lot of new electronic goodies that are under that festive foliage. But there's still a bit that needs to be done helping out your relatives with setting up those new goodies. You'll be uninstalling programs, explaining apps, and speeding up PCs, and making sure that everything is safe and secure.

All of your family (and many of your friends) will be looking to you to answer all of their technology questions. But, in a world of data leaks and daily hacks, many of them won't be asking the right questions. I wanted to build this guide to help you pinpoint some of the best ways to help make your relatives more digitally secure and how to help them understand all of it.

If you're not technically inclined, that's okay too! None of this is
challenging and there's explanations for why it's important.
</div>

<div class="hero">
  <h1>Steps To Take</h1>
</div>

<div class="container content">
{% for page in site.steps %}
  <article class="post">
    <h2 class="post-title">
      <a href="{{ site.baseurl }}{{ page.url }}">
        {{ page.title }}
      </a>
    </h2>
    <h6 id="page-time">{{ page.time }}</h6>
  </article>
{% endfor %}
</div>

<div class="hero">
<h1>FAQs</h1>
</div>

<div class="container content">
{% for faq in site.data.faqs %}
  <h2>{{ faq.question }}</h2>
  <p>{{ faq.answer }}</p>
  <br>
{% endfor %}
</div>
