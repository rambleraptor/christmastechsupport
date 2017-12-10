---
layout: home
---
<div markdown="1" class="container content">
# Techies, Millennials, Ladies and Gentlemen of the Internet
This holiday season, all of you will be participating in a great yearly ritual:
helping out your relatives with their technology issues. You'll be uninstalling
programs, explaining apps, and speeding up PCs.

All of your family (and many of your friends) will be looking to you to answer
all of their technology questions. But, in a world of data leaks and daily
hacks, many of them won't be asking the right questions. I wanted to build this
guide to help you pinpoint some of the best ways to help make your relatives
more digitally secure and how to help them understand all of it.

If you're not technically inclined, that's okay too! None of this is
challenging and there's explanations for why it's important.
</div>

<div class="hero">
  <h1>Steps</h1>
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
