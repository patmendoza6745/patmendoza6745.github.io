---
layout: home
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="home__intro">
<img class="home__photo" src="{{ '/images/profile.jpg' | relative_url }}" alt="">
<div class="home__blurb">
<p class="home__links">
  San Francisco
  · <a href="mailto:{{ site.author.email }}">email</a>
  · <a href="{{ site.author.googlescholar }}">scholar</a>
  · <a href="{{ site.author.orcid }}">orcid</a>
  · <a href="https://github.com/{{ site.author.github }}">github</a>
  · <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">linkedin</a>
</p>
<p>Hi there, I'm Patrick. I like studying RL, alignment, and interpretability.</p>
</div>
</div>

<p class="home__bio" markdown="span">Most recently, I was a Member of Technical Staff at xAI. I studied EECS and Applied Math at UC Berkeley, where I researched speech-language models in the Berkeley Artificial Intelligence Research (BAIR) Lab with [Cheol Jun Cho](https://cheoljun95.github.io/), [Nicholas Lee](https://www.linkedin.com/in/nicholas-lee-74731916a/), and Professor [Gopala Anumanchipalli](https://people.eecs.berkeley.edu/~gopala/), and worked on LLM safety with David Wagner's Research Group alongside [Zhanhao Hu](https://whothu.github.io/) and Professor [David Wagner](https://people.eecs.berkeley.edu/~daw/).</p>

<p class="home__bio" markdown="span">When I'm not working, I enjoy soccer and spending time with my four cats.</p>

<h2 id="work">work</h2>

<div class="publication__list">
{% assign sorted_professional = site.professional | sort: 'date' | reverse %}
{% for post in sorted_professional %}
  {% include archive-single-professional.html %}
{% endfor %}
</div>

<h2 id="teaching">teaching</h2>

<div class="publication__list">
{% assign sorted_teaching = site.teaching | sort: 'date' | reverse %}
{% for post in sorted_teaching %}
  {% include archive-single-teaching.html %}
{% endfor %}
</div>

<h2 id="papers">papers</h2>

<p class="home__note">also on <a href="{{ site.author.googlescholar }}">Google Scholar</a>. a star means equal contribution.</p>

<div class="publication__list">
{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
{% for post in sorted_publications %}
  {% include archive-single-publication.html %}
{% endfor %}
</div>
